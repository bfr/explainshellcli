
# Explain Shell- command line utility

Simple Perl script to fetch and parse shell-command explanations from cli using the excellent explainshell.com service.

If there's something broken or shitty, please make a pull request.

## Prerequisites

You need to have Perl with HTML::Tree and LWP::Simple installed

(For help with installing CPAN-modules, see http://www.cpan.org/modules/INSTALL.html)

## Installation

Just put the `explain` executable somewhere along your $PATH and make sure it is executable

(chmod +x ./explain).

## Usage

```
$ explain COMMAND [PARAMETERS]
```

for example:

```
$ explain ls -la
# list directory contents
# -l     use a long listing format
# -a, --all
       do not ignore entries starting with .
```

## License

Copyright (c) 2013 Roni Kantis (http://www.linkedin.com/in/ronikantis) with the MIT-license, so basically do what you want with it.

