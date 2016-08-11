/******************************************/
/* hpak - package manager for pentesters. */
/******************************************/

 _   _             _    
| | | |_ __   __ _| | __
| |_| | '_ \ / _` | |/ /
|  _  | |_) | (_| |   < 
|_| |_| .__/ \__,_|_|\_\
      |_|               

About
======

Hpak is a package manager for pentesters. 
It will run on any linux distro (Mac?) just need to setup the packages for the OS.
By default hpak will install packages in /opt/pentest/.

TODO
=====

. list all packages in hpak.
. Create .gz package
. Install packages by the web-interface.

Requirements:
=============

. Python 2.7
. Debian/Ubuntu/Mint : sudo apt-get install python-pip
. Archlinux: sudo pacman -S python2-pip


Tested on
==========

. Archlinux
. Debian
. Ubuntu


NOTE: Packages support for debian/ubuntu is not complete!!

Installation
==============

sudo setup.py install

Usage
=======

. Install package:
	.. sudo hpak install package1 package2 etc..

. Remove package:
	.. sudo hpak remove package1 package2 etc..

Create new package
====================

Please create packages! to help hpak grow
Read ./packages/package.example/ and see how it works.

Platforms
===========

. Linux (any)
. Mac ???

Copying
========

Copyright 2016 (C) Hypsurus <hypsurus@mail.ru>
License GPLv3+: GNU GPL version 3 or later <http://gnu.org/licenses/gpl.html>..
