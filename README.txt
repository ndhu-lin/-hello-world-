Git OSX Installer
=================
=================

https://gith
Git GUI / gitk won't open - complain of missing Tcl / Tk Aqua libraries
-----------------------------------------------------------------------

If you don't already have Tcl/Tk Aqua installed on your computer (most
MacOS X installs have it), you will get this error message. To resolve
it, simply go to the website for Tcl / Tk Aqua and download the latest
version:

http://www.categorifiedcoder.info/tcltk/

If you have an older version of Tcl / Tk Aqua, you'll benefit from
upgrading.

More information:

http://code.google.com/p/git-osx-installer/issues/detail?id=41



Installer hangs during install (and I have iPhone developer tools installed)
----------------------------------------------------------------------------

The iPhone developer tools require some kind of gnarly system lock
that causes the MacOS X installer system to hang. Just quit the iPhone
SDK and try again.

More information:

http://code.google.com/p/git-osx-installer/issues/detail?id=35



"git-svn is missing"
--------------------
Mac OS X no longer ships with SVN, and this installer no longer ships
with git-svn support.

Complain about that here:

https://github.com/timcharper/git_osx_installer/issues

Handling of international characters in file is broken
------------------------------------------------------

If you would like some validation, read this: http://is.gd/5NAN9.
You're not alone.

This is not an issue with Git, not the installer. Apparently
subversion has it too.
