在 aws 创建vpc
在新 vpc 中创建子网、安全组、互联网网关
创建 ec2 实例

```
$ ansible-playbook playbook.yml -i inventory -e @vars.yml
```