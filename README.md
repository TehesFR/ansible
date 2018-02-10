# Ansible roles

Personnal set of roles to install and configure web servers when not using Docker...

Please check the example.yml file and the meta/main.yml file of each role to see the OS compatibility.

- apache : Install and configure Apache2
- certbot : Install certbot in order to use let'sencrypt SSL certificates
- change-hostname : Change hostname to match inventory name of the server
- common : Install common packages
- composer : Install composer (require to have PHP already installed)
- console : Install Drupal Console
- docker-ce : Install docker-ce
- drush : Install Drush for Drupal
- fail2ban : Install and configure fail2ban
- memcached : Install memcached
- mysql : Install MySQL 5.7
- new_database : Create new MySQL database, with a new user, and grant all privileges on this database to the user
- new_samba_share : Create a new samba share directory
- new_vhost : Create a new vhost for Apache2
- nginx-reverse-proxy : Install and configure Nginx as a reverse proxy to use it with Apache2
- php : Install PHP 5.6 or 7.1
- phpmyadmin : Install phpmyadmin
- pip : Install pip
- postfix : Install and configure postfix SMTP server
- samba : Install samba
- solr : Install and configure Solr