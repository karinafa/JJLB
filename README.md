MOODLE PARA WINDOWS
==================

Este paquete contiene todo lo que necesita para ejecutar Moodle en una máquina con Windows.

Moodle ha sido empaquetado con Apache, MySQL y PHP.




CONFIGURACIÓN BASE DE DATOS 
=============

Servidor de la base de datos: Localhost

Nombre de la base de datos: moodle

Usuario de la base de datos: root

Contraseña de la base de datos: SIN CONTRASEÑA

Prefijo de tablas: mdl_




USUAIO ADMINISTRADOR
=============

Nombre de usuario adminstrador: admin

Contraseña admin: Kevin12345@




CÓMO USARLO
=============

1. Ejecute 'Iniciar Moodle.exe' para iniciar el sistema.

2. ¡Visite http://localhost/ para usar su sitio Moodle!

3. Otras personas tienen que acceder a través de http://xxx.xxx.xxx.xxx donde
   xx.xx.xx.xx es el número de IP o el nombre de su ordenador.

4. Si desea cerrar el servidor Moodle, use 'Stop Moodle.exe'




INFORMACIÓN TÉCNICA
=====================

1. Iniciar / detener Moodle.exe

'Start Moodle.exe' ejecuta el script de instalación de xampp
ubicado en server/install/install.php. Entonces comenzará apache y mysql.
'Stop Moodle.exe' detiene los procesos apache y mysql.


2. XAMPP (http://www.apachefriends.org/en/xampp.html)

Puede usar archivos ejecutables xampp directamente si lo desea. Son
ubicado en el directorio "servidor".
 

3. Moodle (http://moodle.org/)

Todos los archivos moodle se encuentran en server/moodle/


4. Configuración de rendimiento (http://docs.moodle.org/en/Performance)

Para optimizar su entorno Moodle, consulte los documentos de rendimiento de Moodle.




SOLUCIÓN DE PROBLEMAS
===============

Si 'Start Moodle.exe' no funciona y la ventana se cierra automáticamente,
Es posible que tenga algo bloqueando el puerto 80 en su máquina. Asegúrate de que hay
no hay otros servidores web ejecutándose en este puerto, Skype no está configurado
para usar el puerto 80, los firewalls están abiertos, etc.

Otra razón podría ser porque PHP en este paquete necesita Microsoft
Paquete redistribuible de Visual C ++ 2015 de:
https://www.microsoft.com/en-us/download/details.aspx?id=48145

Para más información visite:
http://docs.moodle.org/en/Complete_install_packages_for_Windows

No cambie el nombre de la carpeta 'servidor /'. De lo contrario, 'Iniciar Moodle.exe' y
'Stop Moodle.exe' dejará de funcionar y tendrá que usar xampp
archivos ejecutables. (xammp-control.exe)



¡Gracias por usar Moodle!

Cuartel general de Moodle (http://moodle.com)