# MyProject

### Installation Nginx
``yum install ngix ``

### Installation Django version 11

yum install epel-release
yum install python-pip
pip install Django==1.11.15

### Issuses
Si vous rencontrez un problème du style permission denied upstream, saisisez la commande suivante
**setsebool -P httpd_can_network_connect 1**
