This is more or less entirely the work of Rafael Corvalan, from 2002 or so.  As
far as I can tell, it has not been maintained for ages, but properly installed,
I find it to be one of the better LDAP editing packages I have used.  Because
I still use it, I'm making it available here.  It may eventually have whatever 
patches might be required to keep it useful and relevant, but for now, it is 
similar, if not identical, to the latest release version.

In order to make use of it, you will also want the following Perl modules:

Net::LDAP

Data::Dumper

Devel::Symdump

Term::ReadLine::GNU

Psh (Similarly unmaintained, but patched to work on current systems, and available in another of my Github repositories.)


------------------------------------------------------------------------------

Original README follows:


ldapsh - The LDAP Shell

This is an LDAP Shell. The purpose is to give an easy access to an LDAP server, and to make easier the directory content changes.
See the POD documentation embedded in the shell itself (using pod2man, pod2text, pod2html or pod2whatever). The HTML version of the documentation is included in the release (ldapsh.html).

Rafael Corvalan
http://sourceforge.net/projects/ldapsh
