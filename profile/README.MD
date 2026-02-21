<html>
<head>
<body>
<a href ="https://man.freebsd.org/cgi/man.cgi?query=os-release&sektion=&manpath=freebsd-release-ports">OS-RELEASE(5)</a>
<p>OS-RELEASE	      File Formats Manual		 OS-RELEASE</p>

<p>NAME
       os-release -- file describing the current OS and	some of	its attributes</p>

<p>DESCRIPTION
       The  os-release	file  is a new-line separated list of key value	pairs.
       The syntax of this file is a reduced sh variable assignment with the
       following restrictions</p>
<ul>
       <li>Strings cannot be concatenated together</li>
       <li>No variable expansion is done</li>
       <li>All shell special characters	must be	quoted as documented in	sh</li>
       <li>Variable assignments	must be	included inside	of  double  quotes if they contain characters outside of A-Z, a-z and 0-9</li>
       <li>All strings should be UTF-8 format</li>
       <li>Non-printable characters should not be used in the strings</li>
</ul>

       <p>Lines starting with the character # are ignored as comments.</p>

VARIABLES
       The following variables are defined by the standard.
       NAME	   A string describing the preferred OS	name.
       VERSION	   Version  string for the OS, in its usual and	customary format.
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

FILES
       /etc/os-release
		   Symbolic link to actual os-release file.
       /var/run/os-release
		   Generated os-release	file describing	the currently  running
		   system.

SEE ALSO
       CPE Specification
		   https://csrc.nist.gov/projects/security-content-automation-
		   protocol/scap-specifications/cpe
       RFC 3986	   https://tools.ietf.org/html/rfc3986
       os-release Specification
		   https://www.linux.org/docs/man5/os-release.html

HISTORY
       This file first appeared	in FreeBSD 13.0.

FreeBSD	15.0		       November	23, 2021		 OS-RELEASE(5)
</body>
<html>