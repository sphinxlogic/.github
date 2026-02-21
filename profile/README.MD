<img src="github-header-banner.png"> 
<p><a href ="https://theoperatingsystemsco.github.io/">Website</a></p>
<p><a href ="https://man.freebsd.org/cgi/man.cgi?query=os-release&sektion=&manpath=freebsd-release-ports">OS-RELEASE(5)</a></p>
<article>
<h1><a href="https://www.cambus.net/cross-building-netbsd-on-linux/">Cross building NetBSD on Linux</a></h1>
<span class="s95"> Frederic Cambus August 29, 2014 [<a href="https://www.cambus.net/categories/netbsd/">NetBSD</a>] </span>
<p>Known for its portability, it might come at no surprise that <strong>NetBSD</strong> (and <strong>pkgsrc</strong> as well) is also easy to <strong>cross build</strong> on other platforms and even other hosts. Building NetBSD on Linux can be very convenient, as it's far easier to get access to high-performance Linux powered machines than to NetBSD ones. So let's go through the process and build a <strong>NetBSD/amd64</strong> release on a Debian host, using an unprivileged user account.</p>
<p>First, we will need to install some development packages on the host machine:</p>
<div class="ccw"><button class="cc " type="button">Copy</button>
<pre style="background-color: #272822; color: #f8f8f2;"><code>apt-get install build-essential zlib1g-dev flex
</code></pre>
</div>
<p>Then, we can download and extract source sets for the NetBSD version we want to build. At the time of writing, latest NetBSD release is 6.1.4:</p>
<div class="ccw"><button class="cc " type="button">Copy</button>
<pre class="language-sh " style="background-color: #272822; color: #f8f8f2;" data-lang="sh"><code class="language-sh" data-lang="sh">wget ftp://ftp.netbsd.org/pub/NetBSD/NetBSD-6.1.4/source/sets/gnusrc.tgz
wget ftp://ftp.netbsd.org/pub/NetBSD/NetBSD-6.1.4/source/sets/sharesrc.tgz
wget ftp://ftp.netbsd.org/pub/NetBSD/NetBSD-6.1.4/source/sets/src.tgz
wget ftp://ftp.netbsd.org/pub/NetBSD/NetBSD-6.1.4/source/sets/syssrc.tgz

<span style="color: #f92672;">for</span> file <span style="color: #f92672;">in *</span>.tgz
<span style="color: #f92672;">do
</span>	tar xfz $file
<span style="color: #f92672;">done
</span></code></pre>
</div>
<p>We can now build the cross compiler:</p>
<div class="ccw"><button class="cc " type="button">Copy</button>
<pre style="background-color: #272822; color: #f8f8f2;"><code>cd usr/src
./build.sh -U -u -m amd64 tools
</code></pre>
</div>
<p>Compilation results:</p>
<div class="ccw"><button class="cc " type="button">Copy</button>
<pre style="background-color: #272822; color: #f8f8f2;"><code>===&gt; Summary of results:
	 build.sh command:    ./build.sh -U -u -m amd64 tools
	 build.sh started:    Thu Aug 28 21:49:19 UTC 2014
	 NetBSD version:      6.1.4
	 MACHINE:             amd64
	 MACHINE_ARCH:        x86_64
	 Build platform:      Linux 3.2.0-4-amd64 x86_64
	 HOST_SH:             /bin/sh
	 No $TOOLDIR/bin/nbmake, needs building.
	 Bootstrapping nbmake
	 TOOLDIR path:        /home/admin/usr/src/obj/tooldir.Linux-3.2.0-4-amd64-x86_64
	 DESTDIR path:        /home/admin/usr/src/obj/destdir.amd64
	 RELEASEDIR path:     /home/admin/usr/src/obj/releasedir
	 Created /home/admin/usr/src/obj/tooldir.Linux-3.2.0-4-amd64-x86_64/bin/nbmake
	 Updated makewrapper: /home/admin/usr/src/obj/tooldir.Linux-3.2.0-4-amd64-x86_64/bin/nbmake-amd64
	 Tools built to /home/admin/usr/src/obj/tooldir.Linux-3.2.0-4-amd64-x86_64
	 build.sh ended:      Thu Aug 28 21:56:48 UTC 2014
</code></pre>
</div>
<p>Here is more information about configuration options used in those examples:</p>
<div class="ccw"><button class="cc " type="button">Copy</button>
<pre style="background-color: #272822; color: #f8f8f2;"><code>    -U             Set MKUNPRIVED=yes; build without requiring root privileges,
                   install from an UNPRIVED build with proper file permissions.
    -u             Set MKUPDATE=yes; do not run "make cleandir" first.
                   Without this, everything is rebuilt, including the tools.
    -m mach        Set MACHINE to mach; not required if NetBSD native.
</code></pre>
</div>
<p>Once our <strong>toolchain</strong> is ready, we can now build NetBSD itself:</p>
<div class="ccw"><button class="cc " type="button">Copy</button>
<pre style="background-color: #272822; color: #f8f8f2;"><code>./build.sh -U -u -m amd64 release
</code></pre>
</div>
<p>Compilation results:</p>
<div class="ccw"><button class="cc " type="button">Copy</button>
<pre style="background-color: #272822; color: #f8f8f2;"><code>===&gt; Summary of results:
         build.sh command:    ./build.sh -U -u -m amd64 release
         build.sh started:    Thu Aug 28 21:57:54 UTC 2014
         NetBSD version:      6.1.4
         MACHINE:             amd64
         MACHINE_ARCH:        x86_64
         Build platform:      Linux 3.2.0-4-amd64 x86_64
         HOST_SH:             /bin/sh
         TOOLDIR path:        /home/admin/usr/src/obj/tooldir.Linux-3.2.0-4-amd64-x86_64
         DESTDIR path:        /home/admin/usr/src/obj/destdir.amd64
         RELEASEDIR path:     /home/admin/usr/src/obj/releasedir
         Updated makewrapper: /home/admin/usr/src/obj/tooldir.Linux-3.2.0-4-amd64-x86_64/bin/nbmake-amd64
         Successful make release
         build.sh ended:      Thu Aug 28 23:21:28 UTC 2014
</code></pre>
</div>
<p>From there, building an ISO image takes only a few seconds:</p>
<div class="ccw"><button class="cc " type="button">Copy</button>
<pre style="background-color: #272822; color: #f8f8f2;"><code>./build.sh -U -u -m amd64 iso-image
</code></pre>
</div>
<p>We can now try to boot the resulting ISO image:</p>
<p><img src="Cross%20building%20NetBSD%20on%20Linux%20_%20Frederic%20Cambus_files/netbsd-bootstrap.png" alt="NetBSD Primary Bootstrap" /></p>
<p><img src="Cross%20building%20NetBSD%20on%20Linux%20_%20Frederic%20Cambus_files/netbsd-installer.png" alt="NetBSD Installer" /></p>
<p>Unsurprisingly, it works as expected! Welcome to NetBSD :-)</p>
<p><strong><a href="#">Back to top</a></strong></p>
</article>
<footer><hr />
<div class="c"><nav></nav>
<p class="s90">Copyright &copy; 2009-2026 Frederic Cambus</p>
<nav>

</nav></div>
</footer>

