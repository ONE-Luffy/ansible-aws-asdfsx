使用方法
```
$ ansible-playbook -i inventory ec2.yml -e "vars_file=./ec2_vars.yml" -e 'action=keypair' --tags keypair
$ ansible-playbook -i inventory ec2.yml -e "vars_file=./ec2_vars.yml" -e 'action=launch' --tags launch
$ ansible-playbook -i inventory ec2.yml -e "vars_file=./ec2_vars.yml" -e 'action=start' --tags start
$ ansible-playbook -i inventory ec2.yml -e "vars_file=./ec2_vars.yml" -e 'action=stop' --tags stop
$ ansible-playbook -i inventory ec2.yml -e "vars_file=./ec2_vars.yml" -e 'action=terminate' --tags terminate
$ ansible-playbook -i inventory ec2.yml -e "vars_file=./ec2_vars.yml" -e 'action=describe' --tags describe
```