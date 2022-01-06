# NAME
***lamp_virtual_host** - create or delete an apache virtual host with database mysql support, custom fast-cgi php version and 
ssl certificate*

# DESCRIPTION
With lamp_virtual_host bash script you can add or delete an apache virtual host to/from your lamp stack. You can also to add a database and choose one of yours fast-cgi php module if installed.

If you choose development environment option, the script will add the ssl certificate with mkcert package if installed on your machine.
If you choose production environment, the script will add the ssl certificate with certbot and let's encrypt. Note that this step requires the dns for domain and aliases setted to your server ip address.

Also you can choose if auto install wordpress or laravel application in your virtual host.

# INSTALLATION
`sudo mv lamp_virtual_host /usr/local/bin`

`sudo chmod +x /usr/local/bin/lamp_virtual_host`

# REQUIREMENTS
- A debian linux distribution like Ubuntu or Debian
- Stack Lamp: Apache, Mysql (optional), Php
- php-fpm module (optional)
- mkcert or certbot for ssl certificate (optional)
       
# AUTHOR: 
lamp_virtual_host is written by Alfio Salanitri www.alfiosalanitri.it and are licensed under the terms of the GNU General Public License, version 2 or higher. 
