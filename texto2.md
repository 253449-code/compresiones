	COMANDOS AWS	
    1 ubuntu
    2  sudo apt update && sudo apt upgrade
    3  sudo apt install git
    4  sudo apt install apache2
    5  ls
    6  sudo systemctl apache2
    7  sudo systemctl status apache2
    8  ls
    9  sudo mv (aquí va el nombre del archivo) /var/www/html
   10  cd /var/www/html
   11  ls
   12  sudo rm index.html
   13  ls
   14  sudo git clone https://github.com/253449-code/prueba3.git (el link pegado de git(code(htpps)))
   15  ls
   16  cd prueba3
   17  sudo mkdir css
   18  cd css
   19  sudo nano 1.txt
   20  cd /etc/apache2
   21  ls
   22  sudo nano apache2.conf (al entrar buscar la linea 160 aprox con ctrl/ luego eliminar la palabra "index" que se encuentra en la parte <Directory /var/www>) (luego salir con ctrlx,yes,etr.)
   23  sudo systemctl restart apache2
   24 sudo poweroff

              certbot
entar a no-ip 
crear una cuenta ingresar datos en dns y acceso remoto -> dns records y poner datos como nombre del host y la ip de la instancia
elegir hopto.org y luego dar en el botón de enable dinamic y después crearlo en el botón verde 
sudo apt install certbot python3-cerbot
y
sudo certbot --apache -d (nombre que pusiste  en no ip con terminación corporation).hopto.org -d (nombre que pusiste  en no ip con terminación corporation) -d (nombre que pusiste  en no ip con terminación corporation).hopto.org
sudo systemctl status apache2
(aquí va un comando que se corta)
sudo nano /etc/ apache2/sites-available/(nombre que pusiste en no ip).conf
(al entar) ServerName (nombre que pusiste en no ip)(salir ns se corta el video)
sudo nano (nombre que pusiste en no ip pero sin la terminación corporation).conf
(al entrar) ServerName (nombre que pusiste en ip).hopto.org
ServerAlias (nombre de noip).org
crtx y
sudo apt apachectl configtest
sudo certbot --apache
(introducir correo electrónico quiero creer que el que pusiste en inicio de cesion en no ip) 
y
y
(nombre de no ip)
sudo certbot --apache
(correo electrónico)
sudo certbot --apache
(nombre de noip).hopto.org
esperar la entrega del certificado y cuando te mande el link copiarlo y pegarlo en el navegador para que pueda ser visible y seguro

27/11

1. sudo apt updatex	
    2  sudo apt upgrade
    3  sudo ufw status verbose
    4  sudo ufw enable
    5  sudo ufw status verbose
    6  sudo ufw status numbered
    7  sudo ufw allow http
    8  sudo ufw status numbered
    9  sudo ufw allow ssh
   12  sudo ufw status numbered
   13  
