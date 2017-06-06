在 aws 创建vpc
在新 vpc 中创建子网、安全组、互联网网关
创建 ec2 实例

首先设置全局环境变量
```
export AWS_ACCESS_KEY_ID=XXXXXXXXXXXXXXXXXXX
export AWS_SECRET_ACCESS_KEY=XXXXXXXXXXXXXXXXXXXXXXX
```

```
$ ansible-playbook playbook.yml -i inventory -e @vars.yml
```

ec2 模块的实际返回结果，和官方示例不太一样，根据需要做修改。
