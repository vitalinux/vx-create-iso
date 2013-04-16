% VX-CREATE-ISO(1) Linux |  Crea un fichero iso de  Vitalinux
% Written by Alberto Gacías
% 2013-04-15


NOMBRE
======
vx-create-iso - Genera un iso de vitalinux


SINOPSIS
========
vx-create-iso Genera un iso de vitalinux (LiveDVD) de un determinado sabor o conjunto de sabores.


DESCRIPCIÓN
===========
Este comando crea un fichero iso de un sabor vitalinux desde los repositorios de migasfree.

En migasfree una **ETIQUETA** es un **atributo** especial. A diferencia de un atributo normal, la etiqueta **nunca** se ejecuta en el cliente migasfree, simplemente es un atributo asociado manualmente a un equipo.

Si se ejecuta **migasfree-tags** sin argumentos, podrás ver todas las etiquetas que están disponibles en el servidor migasfree.

Estas etiquetas, asignadas convenientemente en los repositorios de migasfree, son las que nos permiten instalar/desintalar el conjunto de paquetes que determinan sabor vitalinux.

USO
===
Antes de usar este comando debes editar el fichero de configuracion **/etc/vx-create-iso.conf**

En este fichero la variable **MIGASFREE_TAGS** es una lista de etiquetas que determinarán el sabor del LiveDVD generado.

Una vez configurado el sabor(ó sabores) como root se debe ejecutar: **vx-create-iso**

Este comando necesita de partida una imagen **ubuntu-12.04-desktop-i386.iso** que debe estar almacenada en el disco duro.
Si no tienes esta iso debes bajártela de internet. El comando te pedirá su ubicación.

Despues de aprox. 1 hora (depende mucho del equipo en el que se ejecuta) tendrás la iso del sabor elegido.

Esta iso tendrá los paquetes actualizados con los repositorios y el estado que en migasfree hubiera en ese momento.


COPYRIGHT
=========
Copyright © 2013 Alberto Gacías. License GPLv3+: GNU GPL version 3 or later

<http://gnu.org/licenses/gpl.html>.

This is free software: you are free to change and redistribute it.  There is NO WARRANTY, to the extent permitted by law.


VÉASE TAMBIEN
=============
**vx-create-iso(5)**

**migasfree-tags(1)**
