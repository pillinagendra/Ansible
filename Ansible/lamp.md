https://www.digitalocean.com/community/tutorials/how-to-install-linux-apache-mysql-php-lamp-stack-on-ubuntu-16-04
1.updating the packages
sudo apt-get update
2.installing apache
sudo apt-get install apache2
3.restarting apache
sudo systemctl restart apache2
4.installig php
sudo apt-get install php libapache2-mod-php php-mcrypt php-mysql
5.restaring apache
sudo systemctl restart apache2
6.creaing file in that location
/var/www/html/info.php

<?php
phpinfo();
?>


For centos:

sudo yum install httpd
sudo systemctl start httpd.service
sudo yum install php php-mysql
sudo systemctl restart httpd.service