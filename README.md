# ansible-config-mg

The repository contains ansible script for automating the installation of Mysql, httpd, jenkins, jfrog artigfactory, sonarqube, certbot and nginx. 

The script also deploys a PHP web Application.

Linux Distrubution used;
  * Database: Ubuntu
  * Bastion Host: Amazon Linux
  * Ansible managed nodes: RHEL 8

Dependencies to be installed on the Bastion Host;
  * python 2 or 3
  * python3 -m pip install PyMySQL
  * python3 -m pip install mysql-connector-python
  * ansible-galaxy collection install ansible.posix.
  * ansible-galaxy collection install community.mysql.
  * ansible-galaxy collection install community.general.
