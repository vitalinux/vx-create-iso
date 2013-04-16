% VX-CREATE-ISO.CONF(5) Linux |  Configuration Vitalinux LiveDVD
% Written by Alberto Gacías
% 2013-04-16


NAME
====
vx-create-iso.conf - Configuration Vitalinux LiveDVD


DESCRIPTION
===========
/etc/vx-create-iso.conf contains:


PRODUCT 
-------
Is the product name. Example :

PRODUCT="vitalinux 0.1" 


UBIQUITY_CUSTOM_PACKAGE
-----------------------
Is the ubiquity customize package

UBIQUITY_CUSTOM_PACKAGE="vx-ubiquity"


METAPACKAGE
-----------
Is the metapackage main. Example:

METAPACKAGE="vitalinux"


MIGASFREE_SERVER
----------------
The migasfree server. Example:

MIGASFREE_SERVER="192.168.1.1"


MIGASFREE_VERSION
-----------------
The migasfree version. Example:

MIGASFREE_VERSION="VX-1"


MIGASFREE_REPO_BASE
-------------------
The main repository. In this repository are the packages for install migasfree-client. Example:

MIGASFREE_REPO_BASE="VX-BASE"


MIGASFREE_TAGS
--------------
The flavours of a LiveDVD. Example:

MIGASFREE_TAGS="SBR-Juegos"


COPYRIGHT
=========
Copyright © 2013 Alberto Gacías. License GPLv3+: GNU GPL version 3 or later

<http://gnu.org/licenses/gpl.html>.

This is free software: you are free to change and redistribute it.  There is NO WARRANTY, to the extent permitted by law.


SEE ALSO
========
**vx-create-iso(1)**

**migasfree-tags(1)**
