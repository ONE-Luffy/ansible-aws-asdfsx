使用方法
```
$ ansible-playbook -i contrib/ec2.py nginx.yml -e "nginx_tag=class_nginx" -e 'acname=install' --tags install
$ ansible-playbook -i contrib/ec2.py nginx.yml -e "nginx_tag=class_nginx" -e 'acname=start' --tags start
$ ansible-playbook -i contrib/ec2.py nginx.yml -e "nginx_tag=class_nginx" -e 'acname=restart' --tags restart
$ ansible-playbook -i contrib/ec2.py nginx.yml -e "nginx_tag=class_nginx" -e 'acname=stop' --tags stop
$ ansible-playbook -i contrib/ec2.py nginx.yml -e "nginx_tag=class_nginx" -e 'acname=stop' --tags enable
$ ansible-playbook -i contrib/ec2.py nginx.yml -e "nginx_tag=class_nginx" -e 'acname=stop' --tags disable
```