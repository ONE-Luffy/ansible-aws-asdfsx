使用方法
```
$ ansible-playbook -i contrib/ec2.py mysql.yml -e "mysql_tag=class_database" -e 'action=stop' --tags stop
$ ansible-playbook -i contrib/ec2.py mysql.yml -e "mysql_tag=class_database" -e 'action=start' --tags start
$ ansible-playbook -i contrib/ec2.py mysql.yml -e "mysql_tag=class_database" -e 'action=restart' --tags restart
$ ansible-playbook -i contrib/ec2.py mysql.yml -e "mysql_tag=class_database" -e 'action=add_remote_user' --tags add_remote_user
```