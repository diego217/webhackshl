# Web Hack SHL

WebHackSHL es un conjunto de herramientas desarrollado por Security Hack Labs, para realizar auditorias de seguridad web desde basicas hasta avanzadas, diseñado especialmente para sistemas Debian o basados en el, como Kali Linux. La finalidad de esta herramienta no es fomentar el número de <em>script kiddies</em> y/o <em>crackers</em>. Antes de descargarla tómese el tiempo de leer un poco el código y así mismo entender su funcionamiento, si usted piensa descargar esta herramienta para llevar a cabo actividades ilegales y/o delictivas mejor absténgase de hacerlo. Esta herramienta fue creada con fines éticos y profesionales, también cómo ayuda a especialistas y/o principiantes de Seguridad Informática.


# Usar la herramienta en ArchLinux.
Abran la Terminal:</br>

~$ sudo pacman -S git</br></br>

luego:</br>

~$ git clone https://github.com/sechacklabs/webhackshl.git && cd webhackshl && python webhackshl</br>

Ver todas las opciones de la herramienta:</br>

~$ python webhackshl -h</br>

# Usar la herramienta en Debian.
Abran la Terminal:</br>

~$ sudo apt install git</br></br>

luego:</br>

~$ git clone https://github.com/sechacklabs/webhackshl.git && cd webhackshl && python3 webhackshl</br>

Ver todas las opciones de la herramienta:</br>

~$ python3 webhackshl -h

# Instalación y desinstalación.

Abre el directorio de descarga desde la terminal y ejecuta el siguiente comando:</br>

~$ sudo bash install.sh - Para instalar</br>

~$ sudo bash uninstall.sh - Para desinstalar</br>

# Actualización de la herramienta.

Si usted ha descargado e instalado la herramienta en su equipo usando el script <em>install.sh</em> y desea actualizarla a la versión más reciente deberá realizar lo siguiente:</br>

1. Abrir la carpeta donde ha descargado la herramienta y ejecutar <code>python webhackshl -u</code>. Una vez terminado el proceso deberás ejecutar el script <em>update.sh</em>. Lo cual da cómo resultado:</br>

~$ python webhackshl -u && sudo update.sh</br>

# Soporte y contacto.

Chat: https://chat.securityhacklabs.net/
Blog: https://securityhacklabs.net</br>
Foro: https://foro.securityhacklabs.net/</br>

# Capturas de pantalla.
-![Alt text](https://github.com/sechacklabs/webhackshl/raw/master/screenshots/webhackshl-main.png "Main Screen")          
-![Alt text](https://github.com/sechacklabs/webhackshl/raw/master/screenshots/webhackshl-dorksearch.png "Dork Script")  
-![Alt text](https://github.com/sechacklabs/webhackshl/raw/master/screenshots/webhackshl-dns.png "DNS Search") 
-![Alt text](https://github.com/sechacklabs/webhackshl/raw/master/screenshots/webhackshl-adminfind.png "Admin Finder Script") 

