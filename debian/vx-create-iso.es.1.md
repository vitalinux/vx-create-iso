% VX-CREATE-ISO(1) Linux |  Create a Vitalinux iso
% Written by Alberto Gacías
% 2013-04-15

NAME
====
vx-create-iso - Genera un iso de vitalinux

SYNOPSIS
========
vx-create-iso Genera un iso de vitalinux de un determinado sabor


DESCRIPTION
===========
Este comando crea un fichero iso de un sabor vitalinux desde los repositorios de migasfree

USAGE
=====
Antes de usar este comando debes editar el fichero de configuracion **/etc/vx-create-iso.conf**

En este fichero la variable **MIGASFREE_TAGS** es una lista de etiquetas

En migasfree una ETIQUETA es un atributo especial de migasfree asignado manualmente a un equipo.

Si ejecutas **migasfree-tags** sin argumentos verás todas las etiquetas disponibles en el servidor migasfree.

COPYRIGHT
=========
Copyright © 2013 Alberto Gacías. License GPLv3+: GNU GPL version 3 or later

<http://gnu.org/licenses/gpl.html>.

This is free software: you are free to change and redistribute it.  There is NO WARRANTY, to the extent permitted by law.

SEE ALSO
========
**vx-create-iso(5)**

**migasfree-tags**
