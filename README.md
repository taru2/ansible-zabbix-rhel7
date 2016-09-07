
# Installation fof Zabbix3.0 

clone repository
```
git clone https://github.com/sios-tech/ansible-zabbix-rhel7.git
```

configuration
```
vim ./ansible-zabbix-rhel7/group_vars/zabbix-server-mysql-standalone
```

place of installation
```
vim ./ansible-zabbix-rhel7/hosts
```

execute
```
cd ansible-zabbix-rhel7
ansible-playbook -u root ./zabbix-server-mysql-standalone.yml
```

mysql security setting
```
mysql_secure_installation
```
