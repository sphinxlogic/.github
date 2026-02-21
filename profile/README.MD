
<a href ="https://man.freebsd.org/cgi/man.cgi?query=os-release&sektion=&manpath=freebsd-release-ports">OS-RELEASE(5)</a>
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml"><head><title>os-release</title>
<meta http-equiv="content-type" content="text/html; charset=windows-1252">
<meta name="robots" content="nofollow">
    <link rel="stylesheet" media="screen" href="os-release_files/fixed.css" type="text/css" title="Normal Text">
    <link rel="alternate stylesheet" media="screen" href="os-release_files/fixed_large.css" type="text/css" title="Large Text">
    <link rel="shortcut icon" href="https://man.freebsd.org/favicon.ico" type="image/x-icon">
    <link rel="apple-touch-icon" href="https://man.freebsd.org/favicon.ico" type="image/x-icon">



<meta name="robots" content="nofollow">
<meta content="text/html; charset=windows-1252" http-equiv="Content-Type">
<link rel="search" type="application/opensearchdescription+xml" href="https://www.freebsd.org/opensearch/man.xml" title="FreeBSD Man">
<link rel="search" type="application/opensearchdescription+xml" href="https://www.freebsd.org/opensearch/man-freebsd-release-ports.xml" title="FreeBSD Man+P">

<style type="text/css">
span.footer_links { font-size: small; }
span.space { font-size: xx-small; }
form#man > input, form#man > button { font-size: large; }
form#man > input[name='query'] { text-align: center; }
p#section_links, div#footer { max-width: 50em; }
hr { margin-left: 0em; max-width: 50em; }
a:link  { text-decoration:none; }
a:hover { text-decoration:underline; }

@media only screen and (max-height: 640px), (max-width: 760px) {
  /* hide logo color top */
  body { background: #fff !important; } 

  /* hide menu top */
  div#header, div#menu { display: none !important; }
  // div#content { padding-top: 4.9em; }
  span.spaces { display: none; }

  /* larger search form */
  form#man > input, button { font-size: 200%; }
  form#man > button { font-size: 200%; }
  form#man > input[name='query'] { width: 12em; }
  form#man > select { font-size: 140%; }
}
</style>

</head>
<body>

    <div id="containerwrap">
      <div id="container">
        <span class="txtoffscreen"><a href="#content" title="Skip site navigation" accesskey="1">Skip site
        navigation</a> (1)</span><span class="txtoffscreen"><a href="#content" title="Skip section navigation" accesskey="2">Skip section navigation</a> (2)</span>

        <div id="headercontainer">
          <div id="header">
            <h2 class="blockhide">Header And Logo</h2>

            <div id="headerlogoleft">
              <a href="https://www.freebsd.org/" title="FreeBSD"><img src="os-release_files/banner-red.png" width="457" height="75" alt="FreeBSD"></a>
            </div>

            <div id="headerlogoright">
              <h2 class="blockhide">Peripheral Links</h2>

	      <div class="frontdonateroundbox">
		<div class="frontdonatetop">
		  <div>
		    <b style="display: none;">.</b>
		  </div>
		</div>
		<div class="frontdonatecontent">
		  <a href="https://www.freebsdfoundation.org/donate/">Donate to FreeBSD</a>
		</div>
		<div class="frontdonatebot">
		  <div>
		    <b style="display: none;">.</b>
		  </div>
		</div>
	      </div>

              <div id="search">
		<form method="get" id="search-form" action="https://duckduckgo.com/">
		  <h2 class="blockhide"><label for="words">Search</label></h2>
		  <input type="hidden" name="sites" value="FreeBSD.org">
		  <input type="hidden" name="ka" value="v">
		  <input type="hidden" name="kt" value="v">
		  <input type="hidden" name="kh" value="1">
		  <input type="hidden" name="kj" value="r2">
		  <input id="words" name="q" type="text" size="20" autocapitalize="none" maxlength="255" onfocus="if( this.value==this.defaultValue ) this.value='';" value="Search">
		  <span>&nbsp;</span>
		  <input id="submit" name="submit" type="submit" value="Search">
		</form>
              </div>
            </div>
          </div>

          <h2 class="blockhide">Site Navigation</h2>

	  <div id="menu">
	    <ul class="first">
	      <li><a href="https://www.freebsd.org/">Home</a></li>
	    </ul>
	    <ul>
	      <li><a href="https://www.freebsd.org/about/">About</a>
		<ul>
		  <li><a href="https://www.freebsd.org/projects/newbies/">Introduction</a></li>
		  <li><a href="https://www.freebsd.org/features/">Features</a></li>
		  <li><a href="https://www.freebsd.org/advocacy/">Advocacy</a></li>
		  <li><a href="https://www.freebsd.org/marketing/">Marketing</a></li>
		</ul>
	      </li>
	    </ul>
	    <ul>
	      <li><a href="https://www.freebsd.org/where/">Get FreeBSD</a>
		<ul>
		  <li><a href="https://www.freebsd.org/releases/">Release Information</a></li>
		  <li><a href="https://www.freebsd.org/releng/">Release Engineering</a></li>
		</ul>
	      </li>
	    </ul>
	    <ul>
	      <li><a href="https://www.freebsd.org/docs/">Documentation</a>
		<ul>
		  <li><a href="https://docs.freebsd.org/en/books/faq/">FAQ</a></li>
		  <li><a href="https://docs.freebsd.org/en/books/handbook/">Handbook</a></li>
		  <li><a href="https://docs.freebsd.org/en/books/porters-handbook/">Porter's Handbook</a></li>
		  <li><a href="https://docs.freebsd.org/en//books/developers-handbook/">Developer's Handbook</a></li>
		  <li><a href="https://www.freebsd.org/cgi/man.cgi">Manual Pages</a></li>
		  <li><a href="https://docs.freebsd.org/en/books/fdp-primer/">Documentation Project Primer</a></li>
		  <li><a href="https://www.freebsd.org/docs/books/">All Books and Articles</a></li>
		</ul>
	      </li>
	    </ul>
	    <ul>
	      <li><a href="https://www.freebsd.org/community.html">Community</a>
		<ul>
		  <li><a href="https://www.freebsd.org/community/mailinglists.html">Mailing Lists</a></li>
		  <li><a href="https://forums.freebsd.org/">Forums</a></li>
		  <li><a href="https://www.freebsd.org/usergroups.html">User Groups</a></li>
		  <li><a href="https://www.freebsd.org/events/events.html">Events</a></li>
		</ul>
	      </li>
	    </ul>
	    <ul>
	      <li><a href="https://www.freebsd.org/projects/index.html">Developers</a>
		<ul>
		  <li><a href="https://www.freebsd.org/projects/ideas/ideas.html">Project Ideas</a></li>
		  <li><a href="https://cgit.freebsd.org/">GIT Repository</a></li>
		</ul>
	      </li>
	    </ul>
	    <ul>
	      <li><a href="https://www.freebsd.org/support.html">Support</a>
		<ul>
		  <li><a href="https://www.freebsd.org/commercial/commercial.html">Vendors</a></li>
		  <li><a href="https://security.freebsd.org/">Security Information</a></li>
		  <li><a href="https://bugs.freebsd.org/search/">Bug Reports</a></li>
		  <li><a href="https://www.freebsd.org/support.html">Submit Bug-report</a></li>
		</ul>
	      </li>
	    </ul>
	    <ul>
	      <li><a href="https://www.freebsdfoundation.org/">Foundation</a>
		<ul>
		  <li><a href="https://www.freebsdfoundation.org/donate/">Donate</a></li>
		</ul>
	      </li>
	    </ul>
	  </div> <!-- MENU -->
        </div>

	<div id="content">

<br>
<h1>FreeBSD Manual Pages</h1>

<form id="man" method="get" action="/cgi/man.cgi">
<!-- Manual Page or Keyword Search: -->
<span class="spaces">&nbsp;&nbsp;</span>
<input type="text" id="query" value="os-release" name="query" size="36" autocapitalize="none">
<button type="submit" name="apropos" value="0">man</button>
<button type="submit" name="apropos" value="1">apropos</button>
<br>
<span class="space">&nbsp;</span><br>
<span class="spaces">&nbsp;&nbsp;</span>
<select name="sektion">
<option value="0" selected="selected">All Sections</option>
<option value="1">1 - General Commands</option>
<option value="2">2 - System Calls</option>
<option value="3">3 - Subroutines</option>
<option value="4">4 - Special Files</option>
<option value="5">5 - File Formats</option>
<option value="6">6 - Games</option>
<option value="7">7 - Macros and Conventions</option>
<option value="8">8 - Maintenance Commands</option>
<option value="9">9 - Kernel Interface</option>
<option value="n">n - New Commands</option>
</select>
<select name="manpath">
<option value="FreeBSD 16.0-CURRENT">FreeBSD 16.0-CURRENT</option>
<option value="FreeBSD 15.0-RELEASE">FreeBSD 15.0-RELEASE</option>
<option selected="selected" value="FreeBSD 15.0-RELEASE and Ports">FreeBSD 15.0-RELEASE and Ports</option>
<option value="FreeBSD 15.0-STABLE">FreeBSD 15.0-STABLE</option>
<option value="FreeBSD 14.4-STABLE">FreeBSD 14.4-STABLE</option>
<option value="FreeBSD 14.3-RELEASE">FreeBSD 14.3-RELEASE</option>
<option value="FreeBSD 14.3-RELEASE and Ports">FreeBSD 14.3-RELEASE and Ports</option>
<option value="FreeBSD 14.2-RELEASE">FreeBSD 14.2-RELEASE</option>
<option value="FreeBSD 14.2-RELEASE and Ports">FreeBSD 14.2-RELEASE and Ports</option>
<option value="FreeBSD 14.1-RELEASE">FreeBSD 14.1-RELEASE</option>
<option value="FreeBSD 14.1-RELEASE and Ports">FreeBSD 14.1-RELEASE and Ports</option>
<option value="FreeBSD 14.0-RELEASE">FreeBSD 14.0-RELEASE</option>
<option value="FreeBSD 14.0-RELEASE and Ports">FreeBSD 14.0-RELEASE and Ports</option>
<option value="FreeBSD 13.5-RELEASE">FreeBSD 13.5-RELEASE</option>
<option value="FreeBSD 13.5-RELEASE and Ports">FreeBSD 13.5-RELEASE and Ports</option>
<option value="FreeBSD 13.5-STABLE">FreeBSD 13.5-STABLE</option>
<option value="FreeBSD 13.4-RELEASE">FreeBSD 13.4-RELEASE</option>
<option value="FreeBSD 13.4-RELEASE and Ports">FreeBSD 13.4-RELEASE and Ports</option>
<option value="FreeBSD 13.3-RELEASE">FreeBSD 13.3-RELEASE</option>
<option value="FreeBSD 13.3-RELEASE and Ports">FreeBSD 13.3-RELEASE and Ports</option>
<option value="FreeBSD 13.2-RELEASE">FreeBSD 13.2-RELEASE</option>
<option value="FreeBSD 13.2-RELEASE and Ports">FreeBSD 13.2-RELEASE and Ports</option>
<option value="FreeBSD 13.1-RELEASE">FreeBSD 13.1-RELEASE</option>
<option value="FreeBSD 13.1-RELEASE and Ports">FreeBSD 13.1-RELEASE and Ports</option>
<option value="FreeBSD 13.0-RELEASE">FreeBSD 13.0-RELEASE</option>
<option value="FreeBSD 13.0-RELEASE and Ports">FreeBSD 13.0-RELEASE and Ports</option>
<option value="FreeBSD 12.4-RELEASE">FreeBSD 12.4-RELEASE</option>
<option value="FreeBSD 12.4-RELEASE and Ports">FreeBSD 12.4-RELEASE and Ports</option>
<option value="FreeBSD 12.3-RELEASE">FreeBSD 12.3-RELEASE</option>
<option value="FreeBSD 12.3-RELEASE and Ports">FreeBSD 12.3-RELEASE and Ports</option>
<option value="FreeBSD 12.2-RELEASE">FreeBSD 12.2-RELEASE</option>
<option value="FreeBSD 12.2-RELEASE and Ports">FreeBSD 12.2-RELEASE and Ports</option>
<option value="FreeBSD 12.1-RELEASE">FreeBSD 12.1-RELEASE</option>
<option value="FreeBSD 12.1-RELEASE and Ports">FreeBSD 12.1-RELEASE and Ports</option>
<option value="FreeBSD 12.0-RELEASE">FreeBSD 12.0-RELEASE</option>
<option value="FreeBSD 12.0-RELEASE and Ports">FreeBSD 12.0-RELEASE and Ports</option>
<option value="FreeBSD 11.4-RELEASE">FreeBSD 11.4-RELEASE</option>
<option value="FreeBSD 11.4-RELEASE and Ports">FreeBSD 11.4-RELEASE and Ports</option>
<option value="FreeBSD 11.3-RELEASE">FreeBSD 11.3-RELEASE</option>
<option value="FreeBSD 11.3-RELEASE and Ports">FreeBSD 11.3-RELEASE and Ports</option>
<option value="FreeBSD 11.2-RELEASE">FreeBSD 11.2-RELEASE</option>
<option value="FreeBSD 11.2-RELEASE and Ports">FreeBSD 11.2-RELEASE and Ports</option>
<option value="FreeBSD 11.1-RELEASE">FreeBSD 11.1-RELEASE</option>
<option value="FreeBSD 11.1-RELEASE and Ports">FreeBSD 11.1-RELEASE and Ports</option>
<option value="FreeBSD 11.0-RELEASE">FreeBSD 11.0-RELEASE</option>
<option value="FreeBSD 11.0-RELEASE and Ports">FreeBSD 11.0-RELEASE and Ports</option>
<option value="FreeBSD 10.4-RELEASE">FreeBSD 10.4-RELEASE</option>
<option value="FreeBSD 10.4-RELEASE and Ports">FreeBSD 10.4-RELEASE and Ports</option>
<option value="FreeBSD 10.3-RELEASE">FreeBSD 10.3-RELEASE</option>
<option value="FreeBSD 10.3-RELEASE and Ports">FreeBSD 10.3-RELEASE and Ports</option>
<option value="FreeBSD 10.2-RELEASE">FreeBSD 10.2-RELEASE</option>
<option value="FreeBSD 10.2-RELEASE and Ports">FreeBSD 10.2-RELEASE and Ports</option>
<option value="FreeBSD 10.1-RELEASE">FreeBSD 10.1-RELEASE</option>
<option value="FreeBSD 10.1-RELEASE and Ports">FreeBSD 10.1-RELEASE and Ports</option>
<option value="FreeBSD 10.0-RELEASE">FreeBSD 10.0-RELEASE</option>
<option value="FreeBSD 10.0-RELEASE and Ports">FreeBSD 10.0-RELEASE and Ports</option>
<option value="FreeBSD 9.3-RELEASE">FreeBSD 9.3-RELEASE</option>
<option value="FreeBSD 9.3-RELEASE and Ports">FreeBSD 9.3-RELEASE and Ports</option>
<option value="FreeBSD 9.2-RELEASE">FreeBSD 9.2-RELEASE</option>
<option value="FreeBSD 9.2-RELEASE and Ports">FreeBSD 9.2-RELEASE and Ports</option>
<option value="FreeBSD 9.1-RELEASE">FreeBSD 9.1-RELEASE</option>
<option value="FreeBSD 9.1-RELEASE and Ports">FreeBSD 9.1-RELEASE and Ports</option>
<option value="FreeBSD 9.0-RELEASE">FreeBSD 9.0-RELEASE</option>
<option value="FreeBSD 9.0-RELEASE and Ports">FreeBSD 9.0-RELEASE and Ports</option>
<option value="FreeBSD 8.4-RELEASE">FreeBSD 8.4-RELEASE</option>
<option value="FreeBSD 8.4-RELEASE and Ports">FreeBSD 8.4-RELEASE and Ports</option>
<option value="FreeBSD 8.3-RELEASE">FreeBSD 8.3-RELEASE</option>
<option value="FreeBSD 8.3-RELEASE and Ports">FreeBSD 8.3-RELEASE and Ports</option>
<option value="FreeBSD 8.2-RELEASE">FreeBSD 8.2-RELEASE</option>
<option value="FreeBSD 8.2-RELEASE and Ports">FreeBSD 8.2-RELEASE and Ports</option>
<option value="FreeBSD 8.1-RELEASE">FreeBSD 8.1-RELEASE</option>
<option value="FreeBSD 8.1-RELEASE and Ports">FreeBSD 8.1-RELEASE and Ports</option>
<option value="FreeBSD 8.0-RELEASE">FreeBSD 8.0-RELEASE</option>
<option value="FreeBSD 8.0-RELEASE and Ports">FreeBSD 8.0-RELEASE and Ports</option>
<option value="FreeBSD 7.4-RELEASE">FreeBSD 7.4-RELEASE</option>
<option value="FreeBSD 7.4-RELEASE and Ports">FreeBSD 7.4-RELEASE and Ports</option>
<option value="FreeBSD 7.3-RELEASE">FreeBSD 7.3-RELEASE</option>
<option value="FreeBSD 7.3-RELEASE and Ports">FreeBSD 7.3-RELEASE and Ports</option>
<option value="FreeBSD 7.2-RELEASE">FreeBSD 7.2-RELEASE</option>
<option value="FreeBSD 7.2-RELEASE and Ports">FreeBSD 7.2-RELEASE and Ports</option>
<option value="FreeBSD 7.1-RELEASE">FreeBSD 7.1-RELEASE</option>
<option value="FreeBSD 7.1-RELEASE and Ports">FreeBSD 7.1-RELEASE and Ports</option>
<option value="FreeBSD 7.0-RELEASE">FreeBSD 7.0-RELEASE</option>
<option value="FreeBSD 6.4-RELEASE">FreeBSD 6.4-RELEASE</option>
<option value="FreeBSD 6.4-RELEASE and Ports">FreeBSD 6.4-RELEASE and Ports</option>
<option value="FreeBSD 6.3-RELEASE">FreeBSD 6.3-RELEASE</option>
<option value="FreeBSD 6.3-RELEASE and Ports">FreeBSD 6.3-RELEASE and Ports</option>
<option value="FreeBSD 6.2-RELEASE">FreeBSD 6.2-RELEASE</option>
<option value="FreeBSD 6.1-RELEASE">FreeBSD 6.1-RELEASE</option>
<option value="FreeBSD 6.0-RELEASE">FreeBSD 6.0-RELEASE</option>
<option value="FreeBSD 6.0-RELEASE and Ports">FreeBSD 6.0-RELEASE and Ports</option>
<option value="FreeBSD 5.5-RELEASE">FreeBSD 5.5-RELEASE</option>
<option value="FreeBSD 5.5-RELEASE and Ports">FreeBSD 5.5-RELEASE and Ports</option>
<option value="FreeBSD 5.4-RELEASE">FreeBSD 5.4-RELEASE</option>
<option value="FreeBSD 5.4-RELEASE and Ports">FreeBSD 5.4-RELEASE and Ports</option>
<option value="FreeBSD 5.3-RELEASE">FreeBSD 5.3-RELEASE</option>
<option value="FreeBSD 5.3-RELEASE and Ports">FreeBSD 5.3-RELEASE and Ports</option>
<option value="FreeBSD 5.2.1-RELEASE">FreeBSD 5.2.1-RELEASE</option>
<option value="FreeBSD 5.2.1-RELEASE and Ports">FreeBSD 5.2.1-RELEASE and Ports</option>
<option value="FreeBSD 5.2-RELEASE">FreeBSD 5.2-RELEASE</option>
<option value="FreeBSD 5.2-RELEASE and Ports">FreeBSD 5.2-RELEASE and Ports</option>
<option value="FreeBSD 5.1-RELEASE">FreeBSD 5.1-RELEASE</option>
<option value="FreeBSD 5.0-RELEASE">FreeBSD 5.0-RELEASE</option>
<option value="FreeBSD 4.11-RELEASE">FreeBSD 4.11-RELEASE</option>
<option value="FreeBSD 4.11-RELEASE and Ports">FreeBSD 4.11-RELEASE and Ports</option>
<option value="FreeBSD 4.10-RELEASE">FreeBSD 4.10-RELEASE</option>
<option value="FreeBSD 4.10-RELEASE and Ports">FreeBSD 4.10-RELEASE and Ports</option>
<option value="FreeBSD 4.9-RELEASE">FreeBSD 4.9-RELEASE</option>
<option value="FreeBSD 4.9-RELEASE and Ports">FreeBSD 4.9-RELEASE and Ports</option>
<option value="FreeBSD 4.8-RELEASE">FreeBSD 4.8-RELEASE</option>
<option value="FreeBSD 4.8-RELEASE and Ports">FreeBSD 4.8-RELEASE and Ports</option>
<option value="FreeBSD 4.7-RELEASE">FreeBSD 4.7-RELEASE</option>
<option value="FreeBSD 4.6.2-RELEASE">FreeBSD 4.6.2-RELEASE</option>
<option value="FreeBSD 4.6.2-RELEASE and Ports">FreeBSD 4.6.2-RELEASE and Ports</option>
<option value="FreeBSD 4.6-RELEASE">FreeBSD 4.6-RELEASE</option>
<option value="FreeBSD 4.6-RELEASE and Ports">FreeBSD 4.6-RELEASE and Ports</option>
<option value="FreeBSD 4.5-RELEASE">FreeBSD 4.5-RELEASE</option>
<option value="FreeBSD 4.5-RELEASE and Ports">FreeBSD 4.5-RELEASE and Ports</option>
<option value="FreeBSD 4.4-RELEASE">FreeBSD 4.4-RELEASE</option>
<option value="FreeBSD 4.3-RELEASE">FreeBSD 4.3-RELEASE</option>
<option value="FreeBSD 4.3-RELEASE and Ports">FreeBSD 4.3-RELEASE and Ports</option>
<option value="FreeBSD 4.2-RELEASE">FreeBSD 4.2-RELEASE</option>
<option value="FreeBSD 4.2-RELEASE and Ports">FreeBSD 4.2-RELEASE and Ports</option>
<option value="FreeBSD 4.1.1-RELEASE">FreeBSD 4.1.1-RELEASE</option>
<option value="FreeBSD 4.1.1-RELEASE and Ports">FreeBSD 4.1.1-RELEASE and Ports</option>
<option value="FreeBSD 4.1-RELEASE">FreeBSD 4.1-RELEASE</option>
<option value="FreeBSD 4.0-RELEASE">FreeBSD 4.0-RELEASE</option>
<option value="FreeBSD 3.5.1-RELEASE">FreeBSD 3.5.1-RELEASE</option>
<option value="FreeBSD 3.5.1-RELEASE and Ports">FreeBSD 3.5.1-RELEASE and Ports</option>
<option value="FreeBSD 3.5-RELEASE and Ports">FreeBSD 3.5-RELEASE and Ports</option>
<option value="FreeBSD 3.4-RELEASE">FreeBSD 3.4-RELEASE</option>
<option value="FreeBSD 3.4-RELEASE and Ports">FreeBSD 3.4-RELEASE and Ports</option>
<option value="FreeBSD 3.3-RELEASE">FreeBSD 3.3-RELEASE</option>
<option value="FreeBSD 3.2-RELEASE">FreeBSD 3.2-RELEASE</option>
<option value="FreeBSD 3.1-RELEASE">FreeBSD 3.1-RELEASE</option>
<option value="FreeBSD 3.0-RELEASE">FreeBSD 3.0-RELEASE</option>
<option value="FreeBSD 2.2.8-RELEASE">FreeBSD 2.2.8-RELEASE</option>
<option value="FreeBSD 2.2.8-RELEASE and Ports">FreeBSD 2.2.8-RELEASE and Ports</option>
<option value="FreeBSD 2.2.7-RELEASE">FreeBSD 2.2.7-RELEASE</option>
<option value="FreeBSD 2.2.6-RELEASE">FreeBSD 2.2.6-RELEASE</option>
<option value="FreeBSD 2.2.5-RELEASE">FreeBSD 2.2.5-RELEASE</option>
<option value="FreeBSD 2.2.2-RELEASE">FreeBSD 2.2.2-RELEASE</option>
<option value="FreeBSD 2.2.1-RELEASE">FreeBSD 2.2.1-RELEASE</option>
<option value="FreeBSD 2.1.7.1-RELEASE">FreeBSD 2.1.7.1-RELEASE</option>
<option value="FreeBSD 2.1.6.1-RELEASE">FreeBSD 2.1.6.1-RELEASE</option>
<option value="FreeBSD 2.1.5-RELEASE">FreeBSD 2.1.5-RELEASE</option>
<option value="FreeBSD 2.1.0-RELEASE">FreeBSD 2.1.0-RELEASE</option>
<option value="FreeBSD 2.0.5-RELEASE">FreeBSD 2.0.5-RELEASE</option>
<option value="FreeBSD 2.0-RELEASE">FreeBSD 2.0-RELEASE</option>
<option value="FreeBSD 1.1.5.1-RELEASE">FreeBSD 1.1.5.1-RELEASE</option>
<option value="FreeBSD 1.1-RELEASE">FreeBSD 1.1-RELEASE</option>
<option value="FreeBSD 1.0-RELEASE">FreeBSD 1.0-RELEASE</option>
<option value="FreeBSD Ports 15.0">FreeBSD Ports 15.0</option>
<option value="FreeBSD Ports 14.3">FreeBSD Ports 14.3</option>
<option value="FreeBSD Ports 14.3.quarterly">FreeBSD Ports 14.3.quarterly</option>
<option value="FreeBSD Ports 14.2">FreeBSD Ports 14.2</option>
<option value="FreeBSD Ports 14.1">FreeBSD Ports 14.1</option>
<option value="FreeBSD Ports 14.0">FreeBSD Ports 14.0</option>
<option value="FreeBSD Ports 13.5">FreeBSD Ports 13.5</option>
<option value="FreeBSD Ports 13.4">FreeBSD Ports 13.4</option>
<option value="FreeBSD Ports 13.3">FreeBSD Ports 13.3</option>
<option value="FreeBSD Ports 13.2">FreeBSD Ports 13.2</option>
<option value="FreeBSD Ports 13.1">FreeBSD Ports 13.1</option>
<option value="FreeBSD Ports 13.0">FreeBSD Ports 13.0</option>
<option value="FreeBSD Ports 12.4">FreeBSD Ports 12.4</option>
<option value="FreeBSD Ports 12.3">FreeBSD Ports 12.3</option>
<option value="FreeBSD Ports 12.2">FreeBSD Ports 12.2</option>
<option value="FreeBSD Ports 12.1">FreeBSD Ports 12.1</option>
<option value="FreeBSD Ports 12.0">FreeBSD Ports 12.0</option>
<option value="FreeBSD Ports 11.4">FreeBSD Ports 11.4</option>
<option value="FreeBSD Ports 11.3">FreeBSD Ports 11.3</option>
<option value="FreeBSD Ports 11.2">FreeBSD Ports 11.2</option>
<option value="FreeBSD Ports 11.1">FreeBSD Ports 11.1</option>
<option value="FreeBSD Ports 11.0">FreeBSD Ports 11.0</option>
<option value="FreeBSD Ports 10.4">FreeBSD Ports 10.4</option>
<option value="FreeBSD Ports 10.3">FreeBSD Ports 10.3</option>
<option value="FreeBSD Ports 10.2">FreeBSD Ports 10.2</option>
<option value="FreeBSD Ports 10.1">FreeBSD Ports 10.1</option>
<option value="FreeBSD Ports 10.0">FreeBSD Ports 10.0</option>
<option value="FreeBSD Ports 9.3">FreeBSD Ports 9.3</option>
<option value="FreeBSD Ports 9.2">FreeBSD Ports 9.2</option>
<option value="FreeBSD Ports 9.1">FreeBSD Ports 9.1</option>
<option value="FreeBSD Ports 9.0">FreeBSD Ports 9.0</option>
<option value="FreeBSD Ports 8.4">FreeBSD Ports 8.4</option>
<option value="FreeBSD Ports 8.3">FreeBSD Ports 8.3</option>
<option value="FreeBSD Ports 8.2">FreeBSD Ports 8.2</option>
<option value="FreeBSD Ports 8.1">FreeBSD Ports 8.1</option>
<option value="FreeBSD Ports 8.0">FreeBSD Ports 8.0</option>
<option value="FreeBSD Ports 7.4">FreeBSD Ports 7.4</option>
<option value="FreeBSD Ports 7.3">FreeBSD Ports 7.3</option>
<option value="FreeBSD Ports 7.2">FreeBSD Ports 7.2</option>
<option value="FreeBSD Ports 7.1">FreeBSD Ports 7.1</option>
<option value="FreeBSD Ports 7.0">FreeBSD Ports 7.0</option>
<option value="FreeBSD Ports 6.4">FreeBSD Ports 6.4</option>
<option value="FreeBSD Ports 6.3">FreeBSD Ports 6.3</option>
<option value="FreeBSD Ports 6.2">FreeBSD Ports 6.2</option>
<option value="FreeBSD Ports 6.0">FreeBSD Ports 6.0</option>
<option value="FreeBSD Ports 5.5">FreeBSD Ports 5.5</option>
<option value="FreeBSD Ports 5.4">FreeBSD Ports 5.4</option>
<option value="FreeBSD Ports 5.3">FreeBSD Ports 5.3</option>
<option value="FreeBSD Ports 5.2.1">FreeBSD Ports 5.2.1</option>
<option value="FreeBSD Ports 5.2">FreeBSD Ports 5.2</option>
<option value="FreeBSD Ports 5.1">FreeBSD Ports 5.1</option>
<option value="FreeBSD Ports 4.11">FreeBSD Ports 4.11</option>
<option value="FreeBSD Ports 4.10">FreeBSD Ports 4.10</option>
<option value="FreeBSD Ports 4.9">FreeBSD Ports 4.9</option>
<option value="FreeBSD Ports 4.8">FreeBSD Ports 4.8</option>
<option value="FreeBSD Ports 4.7">FreeBSD Ports 4.7</option>
<option value="FreeBSD Ports 4.6.2">FreeBSD Ports 4.6.2</option>
<option value="FreeBSD Ports 4.6">FreeBSD Ports 4.6</option>
<option value="FreeBSD Ports 4.5">FreeBSD Ports 4.5</option>
<option value="FreeBSD Ports 4.3">FreeBSD Ports 4.3</option>
<option value="FreeBSD Ports 4.2">FreeBSD Ports 4.2</option>
<option value="FreeBSD Ports 4.1.1">FreeBSD Ports 4.1.1</option>
<option value="FreeBSD Ports 3.5.1">FreeBSD Ports 3.5.1</option>
<option value="FreeBSD Ports 3.5">FreeBSD Ports 3.5</option>
<option value="FreeBSD Ports 3.4">FreeBSD Ports 3.4</option>
<option value="FreeBSD Ports 2.2.8">FreeBSD Ports 2.2.8</option>
<option value="4.4BSD Lite2">4.4BSD Lite2</option>
<option value="4.3BSD NET/2">4.3BSD NET/2</option>
<option value="4.3BSD Reno">4.3BSD Reno</option>
<option value="2.11 BSD">2.11 BSD</option>
<option value="2.10 BSD">2.10 BSD</option>
<option value="2.9.1 BSD">2.9.1 BSD</option>
<option value="2.8 BSD">2.8 BSD</option>
<option value="386BSD 0.1">386BSD 0.1</option>
<option value="386BSD 0.0">386BSD 0.0</option>
<option value="CentOS 7.9">CentOS 7.9</option>
<option value="CentOS 7.8">CentOS 7.8</option>
<option value="CentOS 7.7">CentOS 7.7</option>
<option value="CentOS 7.6">CentOS 7.6</option>
<option value="CentOS 7.5">CentOS 7.5</option>
<option value="CentOS 7.4">CentOS 7.4</option>
<option value="CentOS 7.3">CentOS 7.3</option>
<option value="CentOS 7.2">CentOS 7.2</option>
<option value="CentOS 7.1">CentOS 7.1</option>
<option value="CentOS 7.0">CentOS 7.0</option>
<option value="CentOS 6.10">CentOS 6.10</option>
<option value="CentOS 6.9">CentOS 6.9</option>
<option value="CentOS 6.8">CentOS 6.8</option>
<option value="CentOS 6.7">CentOS 6.7</option>
<option value="CentOS 6.6">CentOS 6.6</option>
<option value="CentOS 6.5">CentOS 6.5</option>
<option value="CentOS 6.4">CentOS 6.4</option>
<option value="CentOS 6.3">CentOS 6.3</option>
<option value="CentOS 6.2">CentOS 6.2</option>
<option value="CentOS 6.1">CentOS 6.1</option>
<option value="CentOS 6.0">CentOS 6.0</option>
<option value="CentOS 5.11">CentOS 5.11</option>
<option value="CentOS 5.10">CentOS 5.10</option>
<option value="CentOS 5.9">CentOS 5.9</option>
<option value="CentOS 5.8">CentOS 5.8</option>
<option value="CentOS 5.7">CentOS 5.7</option>
<option value="CentOS 5.6">CentOS 5.6</option>
<option value="CentOS 5.5">CentOS 5.5</option>
<option value="CentOS 5.4">CentOS 5.4</option>
<option value="CentOS 4.8">CentOS 4.8</option>
<option value="CentOS 3.9">CentOS 3.9</option>
<option value="Darwin 8.0.1/ppc">Darwin 8.0.1/ppc</option>
<option value="Darwin 7.0.1">Darwin 7.0.1</option>
<option value="Darwin 6.0.2/x86">Darwin 6.0.2/x86</option>
<option value="Darwin 1.4.1/x86">Darwin 1.4.1/x86</option>
<option value="Darwin 1.3.1/x86">Darwin 1.3.1/x86</option>
<option value="Debian 14.0 unstable">Debian 14.0 unstable</option>
<option value="Debian 13.3.0">Debian 13.3.0</option>
<option value="Debian 12.13.0">Debian 12.13.0</option>
<option value="Debian 11.11.0">Debian 11.11.0</option>
<option value="Debian 10.13.0">Debian 10.13.0</option>
<option value="Debian 9.13.0">Debian 9.13.0</option>
<option value="Debian 8.11.1">Debian 8.11.1</option>
<option value="Debian 7.11.0">Debian 7.11.0</option>
<option value="Debian 6.0.10">Debian 6.0.10</option>
<option value="Debian 5.0.10">Debian 5.0.10</option>
<option value="Debian 4.0.9">Debian 4.0.9</option>
<option value="Debian 3.1.8">Debian 3.1.8</option>
<option value="Debian 2.2.7">Debian 2.2.7</option>
<option value="Debian 2.0.0">Debian 2.0.0</option>
<option value="Dell UNIX SVR4 2.2">Dell UNIX SVR4 2.2</option>
<option value="DragonFly 6.4.2">DragonFly 6.4.2</option>
<option value="DragonFly 5.8.3">DragonFly 5.8.3</option>
<option value="DragonFly 4.8.1">DragonFly 4.8.1</option>
<option value="DragonFly 3.8.2">DragonFly 3.8.2</option>
<option value="DragonFly 2.10.1">DragonFly 2.10.1</option>
<option value="DragonFly 1.12.1">DragonFly 1.12.1</option>
<option value="DragonFly 1.0A">DragonFly 1.0A</option>
<option value="HP-UX 11.22">HP-UX 11.22</option>
<option value="HP-UX 11.20">HP-UX 11.20</option>
<option value="HP-UX 11.11">HP-UX 11.11</option>
<option value="HP-UX 11.00">HP-UX 11.00</option>
<option value="HP-UX 10.20">HP-UX 10.20</option>
<option value="HP-UX 10.10">HP-UX 10.10</option>
<option value="HP-UX 10.01">HP-UX 10.01</option>
<option value="HP-UX 9.07">HP-UX 9.07</option>
<option value="HP-UX 8.07">HP-UX 8.07</option>
<option value="Inferno 4th Edition">Inferno 4th Edition</option>
<option value="IRIX 6.5.30">IRIX 6.5.30</option>
<option value="Linux Slackware 3.1">Linux Slackware 3.1</option>
<option value="MACH 2.5/i386">MACH 2.5/i386</option>
<option value="macOS 26.3">macOS 26.3</option>
<option value="macOS 15.7.4">macOS 15.7.4</option>
<option value="macOS 14.8.4">macOS 14.8.4</option>
<option value="macOS 13.6.5">macOS 13.6.5</option>
<option value="macOS 12.7.3">macOS 12.7.3</option>
<option value="macOS 11.1">macOS 11.1</option>
<option value="macOS 10.15.7">macOS 10.15.7</option>
<option value="macOS 10.13.6">macOS 10.13.6</option>
<option value="macOS 10.12.0">macOS 10.12.0</option>
<option value="Minix 3.3.0">Minix 3.3.0</option>
<option value="Minix 3.2.1">Minix 3.2.1</option>
<option value="Minix 3.2.0">Minix 3.2.0</option>
<option value="Minix 3.1.7">Minix 3.1.7</option>
<option value="Minix 3.1.6">Minix 3.1.6</option>
<option value="Minix 3.1.5">Minix 3.1.5</option>
<option value="Minix 2.0.0">Minix 2.0.0</option>
<option value="NetBSD 10.1">NetBSD 10.1</option>
<option value="NetBSD 10.0">NetBSD 10.0</option>
<option value="NetBSD 9.4">NetBSD 9.4</option>
<option value="NetBSD 9.3">NetBSD 9.3</option>
<option value="NetBSD 9.2">NetBSD 9.2</option>
<option value="NetBSD 9.1">NetBSD 9.1</option>
<option value="NetBSD 9.0">NetBSD 9.0</option>
<option value="NetBSD 8.3">NetBSD 8.3</option>
<option value="NetBSD 8.2">NetBSD 8.2</option>
<option value="NetBSD 8.1">NetBSD 8.1</option>
<option value="NetBSD 8.0">NetBSD 8.0</option>
<option value="NetBSD 7.2">NetBSD 7.2</option>
<option value="NetBSD 7.1.2">NetBSD 7.1.2</option>
<option value="NetBSD 7.1">NetBSD 7.1</option>
<option value="NetBSD 7.0">NetBSD 7.0</option>
<option value="NetBSD 6.1.5">NetBSD 6.1.5</option>
<option value="NetBSD 6.0">NetBSD 6.0</option>
<option value="NetBSD 5.2.3">NetBSD 5.2.3</option>
<option value="NetBSD 5.2">NetBSD 5.2</option>
<option value="NetBSD 5.1">NetBSD 5.1</option>
<option value="NetBSD 5.0">NetBSD 5.0</option>
<option value="NetBSD 4.0.1">NetBSD 4.0.1</option>
<option value="NetBSD 4.0">NetBSD 4.0</option>
<option value="NetBSD 3.1">NetBSD 3.1</option>
<option value="NetBSD 3.0">NetBSD 3.0</option>
<option value="NetBSD 2.1">NetBSD 2.1</option>
<option value="NetBSD 2.0.2">NetBSD 2.0.2</option>
<option value="NetBSD 2.0">NetBSD 2.0</option>
<option value="NetBSD 1.6.2">NetBSD 1.6.2</option>
<option value="NetBSD 1.6.1">NetBSD 1.6.1</option>
<option value="NetBSD 1.6">NetBSD 1.6</option>
<option value="NetBSD 1.5.3">NetBSD 1.5.3</option>
<option value="NetBSD 1.5.2">NetBSD 1.5.2</option>
<option value="NetBSD 1.5.1">NetBSD 1.5.1</option>
<option value="NetBSD 1.5">NetBSD 1.5</option>
<option value="NetBSD 1.4.3">NetBSD 1.4.3</option>
<option value="NetBSD 1.4.2">NetBSD 1.4.2</option>
<option value="NetBSD 1.4.1">NetBSD 1.4.1</option>
<option value="NetBSD 1.4">NetBSD 1.4</option>
<option value="NetBSD 1.3.3">NetBSD 1.3.3</option>
<option value="NetBSD 1.3.2">NetBSD 1.3.2</option>
<option value="NetBSD 1.3.1">NetBSD 1.3.1</option>
<option value="NetBSD 1.3">NetBSD 1.3</option>
<option value="NetBSD 1.2.1">NetBSD 1.2.1</option>
<option value="NetBSD 1.2">NetBSD 1.2</option>
<option value="NetBSD 1.1">NetBSD 1.1</option>
<option value="NetBSD 1.0">NetBSD 1.0</option>
<option value="NeXTSTEP 3.3">NeXTSTEP 3.3</option>
<option value="OpenBSD 7.8">OpenBSD 7.8</option>
<option value="OpenBSD 7.7">OpenBSD 7.7</option>
<option value="OpenBSD 7.6">OpenBSD 7.6</option>
<option value="OpenBSD 7.5">OpenBSD 7.5</option>
<option value="OpenBSD 7.4">OpenBSD 7.4</option>
<option value="OpenBSD 7.3">OpenBSD 7.3</option>
<option value="OpenBSD 7.2">OpenBSD 7.2</option>
<option value="OpenBSD 7.1">OpenBSD 7.1</option>
<option value="OpenBSD 7.0">OpenBSD 7.0</option>
<option value="OpenBSD 6.9">OpenBSD 6.9</option>
<option value="OpenBSD 6.8">OpenBSD 6.8</option>
<option value="OpenBSD 6.7">OpenBSD 6.7</option>
<option value="OpenBSD 6.6">OpenBSD 6.6</option>
<option value="OpenBSD 6.5">OpenBSD 6.5</option>
<option value="OpenBSD 6.4">OpenBSD 6.4</option>
<option value="OpenBSD 6.3">OpenBSD 6.3</option>
<option value="OpenBSD 6.2">OpenBSD 6.2</option>
<option value="OpenBSD 6.1">OpenBSD 6.1</option>
<option value="OpenBSD 6.0">OpenBSD 6.0</option>
<option value="OpenBSD 5.9">OpenBSD 5.9</option>
<option value="OpenBSD 5.8">OpenBSD 5.8</option>
<option value="OpenBSD 5.7">OpenBSD 5.7</option>
<option value="OpenBSD 5.6">OpenBSD 5.6</option>
<option value="OpenBSD 5.5">OpenBSD 5.5</option>
<option value="OpenBSD 5.4">OpenBSD 5.4</option>
<option value="OpenBSD 5.3">OpenBSD 5.3</option>
<option value="OpenBSD 5.2">OpenBSD 5.2</option>
<option value="OpenBSD 5.1">OpenBSD 5.1</option>
<option value="OpenBSD 5.0">OpenBSD 5.0</option>
<option value="OpenBSD 4.9">OpenBSD 4.9</option>
<option value="OpenBSD 4.8">OpenBSD 4.8</option>
<option value="OpenBSD 4.7">OpenBSD 4.7</option>
<option value="OpenBSD 4.6">OpenBSD 4.6</option>
<option value="OpenBSD 4.5">OpenBSD 4.5</option>
<option value="OpenBSD 4.4">OpenBSD 4.4</option>
<option value="OpenBSD 4.3">OpenBSD 4.3</option>
<option value="OpenBSD 4.2">OpenBSD 4.2</option>
<option value="OpenBSD 4.1">OpenBSD 4.1</option>
<option value="OpenBSD 4.0">OpenBSD 4.0</option>
<option value="OpenBSD 3.9">OpenBSD 3.9</option>
<option value="OpenBSD 3.8">OpenBSD 3.8</option>
<option value="OpenBSD 3.7">OpenBSD 3.7</option>
<option value="OpenBSD 3.6">OpenBSD 3.6</option>
<option value="OpenBSD 3.5">OpenBSD 3.5</option>
<option value="OpenBSD 3.4">OpenBSD 3.4</option>
<option value="OpenBSD 3.3">OpenBSD 3.3</option>
<option value="OpenBSD 3.2">OpenBSD 3.2</option>
<option value="OpenBSD 3.1">OpenBSD 3.1</option>
<option value="OpenBSD 3.0">OpenBSD 3.0</option>
<option value="OpenBSD 2.9">OpenBSD 2.9</option>
<option value="OpenBSD 2.8">OpenBSD 2.8</option>
<option value="OpenBSD 2.7">OpenBSD 2.7</option>
<option value="OpenBSD 2.6">OpenBSD 2.6</option>
<option value="OpenBSD 2.5">OpenBSD 2.5</option>
<option value="OpenBSD 2.4">OpenBSD 2.4</option>
<option value="OpenBSD 2.3">OpenBSD 2.3</option>
<option value="OpenBSD 2.2">OpenBSD 2.2</option>
<option value="OpenBSD 2.1">OpenBSD 2.1</option>
<option value="OpenBSD 2.0">OpenBSD 2.0</option>
<option value="OpenDarwin 7.2.1">OpenDarwin 7.2.1</option>
<option value="OpenDarwin 6.6.2/x86">OpenDarwin 6.6.2/x86</option>
<option value="OpenDarwin 6.6.1/x86">OpenDarwin 6.6.1/x86</option>
<option value="OpenDarwin 20030208pre4/ppc">OpenDarwin 20030208pre4/ppc</option>
<option value="OpenIndiana 2024.10">OpenIndiana 2024.10</option>
<option value="OpenIndiana 2022.10">OpenIndiana 2022.10</option>
<option value="OpenIndiana 2020.10">OpenIndiana 2020.10</option>
<option value="OpenIndiana 2017.10">OpenIndiana 2017.10</option>
<option value="OpenIndiana 2015.10">OpenIndiana 2015.10</option>
<option value="OpenIndiana 2013.08">OpenIndiana 2013.08</option>
<option value="OpenSolaris 2010.03">OpenSolaris 2010.03</option>
<option value="OpenSolaris 2009.06">OpenSolaris 2009.06</option>
<option value="OpenStep 4.2">OpenStep 4.2</option>
<option value="openSUSE 42.3">openSUSE 42.3</option>
<option value="openSUSE 42.2">openSUSE 42.2</option>
<option value="openSUSE 42.1">openSUSE 42.1</option>
<option value="openSUSE 16.0">openSUSE 16.0</option>
<option value="openSUSE 15.6">openSUSE 15.6</option>
<option value="openSUSE 15.5">openSUSE 15.5</option>
<option value="openSUSE 15.4">openSUSE 15.4</option>
<option value="openSUSE 15.3">openSUSE 15.3</option>
<option value="openSUSE 15.2">openSUSE 15.2</option>
<option value="openSUSE 15.1">openSUSE 15.1</option>
<option value="openSUSE 15.0">openSUSE 15.0</option>
<option value="openSUSE 13.2">openSUSE 13.2</option>
<option value="openSUSE 13.1">openSUSE 13.1</option>
<option value="openSUSE 11.4">openSUSE 11.4</option>
<option value="openSUSE 11.3">openSUSE 11.3</option>
<option value="openSUSE 11.2">openSUSE 11.2</option>
<option value="openSUSE 10.3">openSUSE 10.3</option>
<option value="openSUSE 10.2">openSUSE 10.2</option>
<option value="OSF1 V5.1/alpha">OSF1 V5.1/alpha</option>
<option value="OSF1 V4.0/alpha">OSF1 V4.0/alpha</option>
<option value="OSF1 V1.0/mips">OSF1 V1.0/mips</option>
<option value="Plan 9">Plan 9</option>
<option value="Red Hat 9.0">Red Hat 9.0</option>
<option value="Red Hat 8.0">Red Hat 8.0</option>
<option value="Red Hat 7.3">Red Hat 7.3</option>
<option value="Red Hat 7.2">Red Hat 7.2</option>
<option value="Red Hat 7.1">Red Hat 7.1</option>
<option value="Red Hat 7.0">Red Hat 7.0</option>
<option value="Red Hat 6.2">Red Hat 6.2</option>
<option value="Red Hat 6.1">Red Hat 6.1</option>
<option value="Red Hat 5.2">Red Hat 5.2</option>
<option value="Red Hat 5.0">Red Hat 5.0</option>
<option value="Red Hat 4.2">Red Hat 4.2</option>
<option value="Rhapsody DR1">Rhapsody DR1</option>
<option value="Rhapsody DR2">Rhapsody DR2</option>
<option value="Rocky 10.1">Rocky 10.1</option>
<option value="Rocky 10.0">Rocky 10.0</option>
<option value="Rocky 9.7">Rocky 9.7</option>
<option value="Rocky 9.6">Rocky 9.6</option>
<option value="Rocky 9.5">Rocky 9.5</option>
<option value="Rocky 9.4">Rocky 9.4</option>
<option value="Rocky 9.3">Rocky 9.3</option>
<option value="Rocky 9.2">Rocky 9.2</option>
<option value="Rocky 9.1">Rocky 9.1</option>
<option value="Rocky 9.0">Rocky 9.0</option>
<option value="Rocky 8.10">Rocky 8.10</option>
<option value="Rocky 8.9">Rocky 8.9</option>
<option value="Rocky 8.8">Rocky 8.8</option>
<option value="Rocky 8.7">Rocky 8.7</option>
<option value="Rocky 8.6">Rocky 8.6</option>
<option value="Rocky 8.5">Rocky 8.5</option>
<option value="Rocky 8.4">Rocky 8.4</option>
<option value="Rocky 8.3">Rocky 8.3</option>
<option value="Sun UNIX 0.4">Sun UNIX 0.4</option>
<option value="SunOS 5.10">SunOS 5.10</option>
<option value="SunOS 5.9">SunOS 5.9</option>
<option value="SunOS 5.8">SunOS 5.8</option>
<option value="SunOS 5.7">SunOS 5.7</option>
<option value="SunOS 5.6">SunOS 5.6</option>
<option value="SunOS 5.5.1">SunOS 5.5.1</option>
<option value="SunOS 4.1.3">SunOS 4.1.3</option>
<option value="SuSE 11.3">SuSE 11.3</option>
<option value="SuSE 11.2">SuSE 11.2</option>
<option value="SuSE 11.1">SuSE 11.1</option>
<option value="SuSE 11.0">SuSE 11.0</option>
<option value="SuSE 10.3">SuSE 10.3</option>
<option value="SuSE 10.2">SuSE 10.2</option>
<option value="SuSE 10.1">SuSE 10.1</option>
<option value="SuSE 10.0">SuSE 10.0</option>
<option value="SuSE 9.3">SuSE 9.3</option>
<option value="SuSE 9.2">SuSE 9.2</option>
<option value="SuSE 8.2">SuSE 8.2</option>
<option value="SuSE 8.1">SuSE 8.1</option>
<option value="SuSE 8.0">SuSE 8.0</option>
<option value="SuSE 7.3">SuSE 7.3</option>
<option value="SuSE 7.2">SuSE 7.2</option>
<option value="SuSE 7.1">SuSE 7.1</option>
<option value="SuSE 7.0">SuSE 7.0</option>
<option value="SuSE 6.4">SuSE 6.4</option>
<option value="SuSE 6.3">SuSE 6.3</option>
<option value="SuSE 6.1">SuSE 6.1</option>
<option value="SuSE 6.0">SuSE 6.0</option>
<option value="SuSE 5.3">SuSE 5.3</option>
<option value="SuSE 5.2">SuSE 5.2</option>
<option value="SuSE 5.0">SuSE 5.0</option>
<option value="SuSE 4.3">SuSE 4.3</option>
<option value="SuSE ES 10 SP1">SuSE ES 10 SP1</option>
<option value="Ubuntu 24.04 noble">Ubuntu 24.04 noble</option>
<option value="Ubuntu 23.10 mantic">Ubuntu 23.10 mantic</option>
<option value="Ubuntu 22.04 jammy">Ubuntu 22.04 jammy</option>
<option value="Ubuntu 20.04 focal">Ubuntu 20.04 focal</option>
<option value="Ubuntu 18.04 bionic">Ubuntu 18.04 bionic</option>
<option value="Ubuntu 16.04 xenial">Ubuntu 16.04 xenial</option>
<option value="Ubuntu 14.04 trusty">Ubuntu 14.04 trusty</option>
<option value="ULTRIX 4.2">ULTRIX 4.2</option>
<option value="Ultrix-32 2.0/VAX">Ultrix-32 2.0/VAX</option>
<option value="Unix Seventh Edition">Unix Seventh Edition</option>
<option value="X11R7.4">X11R7.4</option>
<option value="X11R7.3.2">X11R7.3.2</option>
<option value="X11R7.2">X11R7.2</option>
<option value="X11R6.9.0">X11R6.9.0</option>
<option value="X11R6.8.2">X11R6.8.2</option>
<option value="X11R6.7.0">X11R6.7.0</option>
<option value="XFree86 4.8.0">XFree86 4.8.0</option>
<option value="XFree86 4.7.0">XFree86 4.7.0</option>
<option value="XFree86 4.6.0">XFree86 4.6.0</option>
<option value="XFree86 4.5.0">XFree86 4.5.0</option>
<option value="XFree86 4.4.0">XFree86 4.4.0</option>
<option value="XFree86 4.3.0">XFree86 4.3.0</option>
<option value="XFree86 4.2.99.3">XFree86 4.2.99.3</option>
<option value="XFree86 4.2.0">XFree86 4.2.0</option>
<option value="XFree86 4.1.0">XFree86 4.1.0</option>
<option value="XFree86 4.0.2">XFree86 4.0.2</option>
<option value="XFree86 4.0.1">XFree86 4.0.1</option>
<option value="XFree86 4.0">XFree86 4.0</option>
<option value="XFree86 3.3.6">XFree86 3.3.6</option>
<option value="XFree86 3.3">XFree86 3.3</option>
<option value="XFree86 2.1">XFree86 2.1</option>
</select>
<select name="format">
<option value="html" selected="selected">html</option>
<option value="pdf">pdf</option>
<option value="ascii">ascii</option>
</select>
</form>

<br>
<span class="footer_links">
  <a href="https://man.freebsd.org/cgi/man.cgi">home</a> |
  <a href="https://man.freebsd.org/cgi/man.cgi/help.html">help</a>
</span>
<hr>
<pre><i>OS-RELEASE</i>(5)		      File Formats Manual		 <i>OS-RELEASE</i>(5)

<a name="NAME" href="#end"><b>NAME</b></a>
       os-release -- file describing the current OS and	some of	its attributes

<a name="DESCRIPTION" href="#end"><b>DESCRIPTION</b></a>
       The  <b>os-release</b>	file  is a new-line separated list of key value	pairs.
       The syntax of this file is a reduced <a href="https://man.freebsd.org/cgi/man.cgi?query=sh&amp;sektion=1&amp;apropos=0&amp;manpath=FreeBSD+15.0-RELEASE+and+Ports"><i>sh</i>(1)</a> variable assignment with the
       following restrictions:

       <b>•</b>   Strings cannot be concatenated together

       <b>•</b>   No variable expansion is done

       <b>•</b>   All shell special characters	must be	quoted as documented in	<a href="https://man.freebsd.org/cgi/man.cgi?query=sh&amp;sektion=1&amp;apropos=0&amp;manpath=FreeBSD+15.0-RELEASE+and+Ports"><i>sh</i>(1)</a>

       <b>•</b>   Variable assignments	must be	included inside	of  double  quotes  if
	   they	contain	characters outside of A-Z, a-z and 0-9

       <b>•</b>   All strings should be UTF-8 format

       <b>•</b>   Non-printable characters should not be used in the strings

       Lines starting with the character `#' are ignored as comments.

<a name="VARIABLES" href="#end"><b>VARIABLES</b></a>
       The following variables are defined by the standard.
       NAME	   A string describing the preferred OS	name.
       VERSION	   Version  string for the OS, in its usual and	customary for-
		   mat.
       ID	   Lower case version of the name with	only  a-z,  0-9,  `.',
		   `-',	and `_'.
       VERSION_ID  Lower  case version of the version with only	a-z, 0-9, `.',
		   `-',	and `_'.
       PRETTY_NAME
		   A pretty version of the name	presented to  the  user.   May
		   contain release information.
       ANSI_COLOR  Suggested  color  presentation  for	the  OS.   This	string
		   should  be  suitable	 for  inclusion	 within	 an  ESC  [  m
		   ANSI/ECMA-48	 escape	 sequence to render the	OS in its pre-
		   ferred color.  This variable	is optional.
       CPE_NAME	   A CPE name for the operating	system.	 This field shall fol-
		   low the NIST	Common Platform	Enumeration specification.
       HOME_URL
       SUPPORT_URL
       BUG_REPORT_URL
       PRIVACY_POLICY_URL
		   Links on the	internet, in RFC 3986 format for different as-
		   pects of this OS.  These variables are optional.
       BUILD_ID	   A string identifying	the build.  This variable is optional.
       VARIANT	   A string describing the variant of this  operating  system.
		   This	variable is optional.
       VARIANT_ID  Lower  case version of the variant with only	a-z, 0-9, `.',
		   `-',	and `_'.  This variable	is optional.

       All other variables have	no standard-defined meaning.

<a name="FILES" href="#end"><b>FILES</b></a>
       <i>/etc/os-release</i>
		   Symbolic link to actual <i>os-release</i> file.
       <i>/var/run/os-release</i>
		   Generated os-release	file describing	the currently  running
		   system.

<a name="SEE_ALSO" href="#end"><b>SEE ALSO</b></a>
       CPE Specification
		   <a href="https://csrc.nist.gov/projects/security-content-automation-">https://csrc.nist.gov/projects/security-content-automation-</a>
		   protocol/scap-specifications/cpe
       RFC 3986	   <a href="https://tools.ietf.org/html/rfc3986">https://tools.ietf.org/html/rfc3986</a>
       os-release Specification
		   <a href="https://www.linux.org/docs/man5/os-release.html">https://www.linux.org/docs/man5/os-release.html</a>

<a name="HISTORY" href="#end"><b>HISTORY</b></a>
       This file first appeared	in FreeBSD 13.0.

FreeBSD	15.0		       November	23, 2021		 <i>OS-RELEASE</i>(5)
</pre>
<a name="end">
<hr>

</a><p id="section_links"><a name="end">
</a><a href="#NAME">NAME</a> |
<a href="#DESCRIPTION">DESCRIPTION</a> |
<a href="#VARIABLES">VARIABLES</a> |
<a href="#FILES">FILES</a> |
<a href="#SEE_ALSO">SEE ALSO</a> |
<a href="#HISTORY">HISTORY</a>
</p>

<p align="left">Want to link to this manual page? Use this URL:<br>&lt;<a href="https://man.freebsd.org/cgi/man.cgi?query=os-release&amp;manpath=FreeBSD+15.0-RELEASE+and+Ports">https://man.freebsd.org/cgi/man.cgi?query=os-release&amp;manpath=FreeBSD+15.0-RELEASE+and+Ports</a>&gt;</p>
<span class="footer_links">
  <a href="https://man.freebsd.org/cgi/man.cgi">home</a>
| <a href="https://man.freebsd.org/cgi/man.cgi/help.html">help</a>
</span>

<hr noshade="noshade">
	</div>
        <div id="footer">
          <a href="https://www.freebsd.org/copyright/">Legal Notices</a> | © 1995-2026
          The FreeBSD Project. All rights reserved.<br>
	  <address><a href="https://www.freebsd.org/mailto/">Contact</a><br></address>
        </div>
      </div>
    </div>
  

</body></html>