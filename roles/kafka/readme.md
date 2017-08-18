使用方法
```
$ ansible-playbook -i contrib/ec2.py kafka.yml -e "kafka_tag=class_kafka" -e 'acname=install' --tags install
$ ansible-playbook -i contrib/ec2.py kafka.yml -e "kafka_tag=class_kafka" -e 'acname=start' --tags start
$ ansible-playbook -i contrib/ec2.py kafka.yml -e "kafka_tag=class_kafka" -e 'acname=stop' --tags stop
$ ansible-playbook -i contrib/ec2.py kafka.yml -e "kafka_tag=class_kafka" -e 'acname=uninstall' --tags uninstall
$ ansible-playbook -i contrib/ec2.py kafka.yml -e "kafka_tag=class_kafka" -e 'acname=info' --tags info
```