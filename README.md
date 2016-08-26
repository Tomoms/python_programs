# python_programs
A collection of my personal python3 scripts

--------------------------------------------

1) chgbrightness

What it is:

A simple tool to increase/decrease screen brightness on laptops with (at least) a Intel integrated GPU. It needs to be run as root but can be associated to a keyboard shortcut after adding

`username ALL=(root) NOPASSWD: /usr/local/bin/chgbrightness`

at the end of the sudo config file (edited via 'sudo visudo') so that the password is not required. It should be possible to do something similar on systems that use su instead of sudo.

How to install: download the raw file, and then run

`$ sudo install chgbrightness /usr/local/bin`

How to use:

`$ sudo chgbrightness [OPTIONS]`

OPTIONS:

inc NUMBER = increases brightness by the specified number of levels. If no number is specified, falls back to 40.

dec NUMBER = decreases brightness by the specified number of levels. If no number is specified, falls back to 40.
