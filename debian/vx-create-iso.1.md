% VX-CREATE-ISO(1) Linux |  Create a Vitalinux iso
% Written by Alberto Gacías
% 2013-04-15

NAME
====
vx-create-iso - Create a vitalinux iso

SYNOPSIS
========
vx-create-iso create a vitalinux flavour iso file


DESCRIPTION
===========
This command create a iso file of a flavour vitalinux from the repositories migasfree

USAGE
=====
Before you use this command you must edit the configuration file **/etc/vx-create-iso.conf**

In this configuration file the variable **MIGASFREE_TAGS** is a tags list.

In migasfree a TAG is a special migasfree's attribute assigned manually to a computer.

If you run **migasfree-tags** without arguments you will see all availables tags in migasfree server.

COPYRIGHT
=========
Copyright © 2013 Alberto Gacías. License GPLv3+: GNU GPL version 3 or later

<http://gnu.org/licenses/gpl.html>.

This is free software: you are free to change and redistribute it.  There is NO WARRANTY, to the extent permitted by law.

SEE ALSO
========
**vx-create-iso(5)**

**migasfree-tags**
