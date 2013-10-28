Explain Shell- command line utility
===============

Simple Perl script to fetch and parse shell-command explanations from cli using the excellent explainshell.com service.

If there's something broken or shitty, please make a pull request.

**INSTALLATION**

Just put "explain"-file somewhere along your $PATH and make it executable

(chmod +x ./explain).

You need to have Perl with HTML::Tree and LWP::Simple installed. 

(For help with installing CPAN-modules, see http://www.cpan.org/modules/INSTALL.html)

**USAGE**

~ $ explain COMMAND [PARAMETERS]

for example:

	~ $ explain ls -la

	  # list directory contents
	  #   -l     use a long listing format
	  #   -a, --all
         do not ignore entries starting with .
         
**LICENSE**

Copyright (c) 2013 Roni Kantis (http://www.linkedin.com/in/ronikantis) with the MIT-license, so basically do what you want with it.