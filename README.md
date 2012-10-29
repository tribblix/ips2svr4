ips2svr4
========

Conversion scripts for taking IPS packages (either from an installed
system or from the repo created from an Illumos build) and creating an
equivalent SCR4 package.

pkg_name.sh - an ugly way to translate IPS package names to SVR4 names

ips2svr4.sh - script to convert a package from an installed system
repo2svr4.sh - script to convert a package from an Illumos build

repo_all.sh, mk_all.sh - wrappers to create all packages

Thes have my own build locations hardcoded, which will need fixing -
search for "ptribble" and "/var/tmp" in the scripts and put in whatever
makes sense for your own system

Known issues
============

Not all package attributes are handled correctly.

Editable files aren't handled as such.
