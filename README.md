# NAME
	lamp_virtual_host - create or delete an apache virtual host with database mysql

# SYNOPSIS
`cd /path/to/your/directory/websites`

`lamp_virtual_host www.example.com/`

# DESCRIPTION
lamp_virtual_host is a simple bash script for debian machines that create or delete an apache virtual host
	
It's possible create or delete a database mysql and choose a different php-fpm version

# INSTALLATION
`sudo mv lamp_virtual_host /usr/bin`

`sudo chmod +x /usr/bin/lamp_virtual_host`

# REQUIREMENTS
- A debian linux distribution like Ubuntu
- Stack Lamp: Apache, Mysql (optional), Php
- php-fpm module (optional)
- mkcert for ssl certificate
       
# AUTHOR: 
lamp_virtual_host is written by Alfio Salanitri www.alfiosalanitri.it and are licensed under the terms of the GNU General Public License, version 2 or higher. 
