Ansible Role : Percona MySQL 56 setup on centos 7/Rhel 7

Example : 

ansible-playbook percona.yml --extra-vars "mysql_new_db=pocdv1"

Role Variables:

Mysql OS username :

mysql_user: mysql

MySQL OS User Group:

mysql_group: mysql

MySQL Database root password

db_root_password: mysql4dba

OS mysql Password 

#Password created using openssl for os user -- openssl passwd -1 -salt xyz <YourPassword>

mysql_os_user_pass: '$1$xyz$WeYslt3rVQ4Niqp.QCXOb.'

Author : Uma M Katru
