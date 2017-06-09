使用方法
```
$ ansible-playbook -i inventory,contrib/ec2.py zookeeper.yml -e "zookeeper_tag=class2_zookeeper" -e 'action=install' --tags install
$ ansible-playbook -i inventory,contrib/ec2.py zookeeper.yml -e "zookeeper_tag=class2_zookeeper" -e 'action=start' --tags start
$ ansible-playbook -i inventory,contrib/ec2.py zookeeper.yml -e "zookeeper_tag=class2_zookeeper" -e 'action=stop' --tags stop
$ ansible-playbook -i inventory,contrib/ec2.py zookeeper.yml -e "zookeeper_tag=class2_zookeeper" -e 'action=uninstall' --tags uninstall
$ ansible-playbook -i inventory,contrib/ec2.py zookeeper.yml -e "zookeeper_tag=class2_zookeeper" -e 'action=info' --tags info
$ ansible-playbook -i inventory,contrib/ec2.py zookeeper.yml -e "zookeeper_tag=class2_zookeeper" -e 'action=describe' --tags describe
```