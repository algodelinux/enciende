enciende
========

Script para encender equipos en la red del centro   
      
   
Instalación
-----------

La forma más sencilla de instalarlo es ejecutar los siguientes comandos:

   wget --no-check-certificate -O /usr/local/sbin/enciende https://raw.githubusercontent.com/algodelinux/enciende/master/enciende  
   chmod 755 /usr/local/sbin/enciende  
   
   
Uso
---

* Es necesario introducir el nombre de la máquina como parámetro.   
* Si no se introduce el nombre como parámetro, mostrará un mensaje informativo con la sintaxis del comando.   
* Primero se busca la MAC del equipo en LDAP y si se encuentra, se enciende.   
* Si no se encuentra, se busca en en ficheros csv que almacenan el nombre del host y su mac.   
  
   
Sintaxis
--------

```bash
enciende [nombre-del-host]
```
   
   
Ejemplos
--------

```bash
# enciende infolab01-u01
```
   
   
Authors
-------

Esteban M. Navas <algodelinux@gmail.com>   
Fecha creación:      09/10/2013   
Última modificación: 19/09/2020   
