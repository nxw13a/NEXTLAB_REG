to OPEN the NEXTLAB_SERVER
download 7ZIP: http://www.7-zip.org/
click right on it: the 7 zip should show up and 
click on archieve
and then enter password
The password is at Admin and Webmaster (please ask them).

use this command after you change the website through WinSCP
sudo rm -rf /var/www/html/*
sudo mv /home/nextlab/NEXTLAB_REG/* /var/www/html/

HOW TO INSTALL SSL certification:
https://www.digicert.com/csr-ssl-installation/ubuntu-server-with-apache2-openssl.htm