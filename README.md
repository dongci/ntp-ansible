ansible-base:
------------------------------------------------------
1> Edit the ./inventory/hosts configuration file

```
[jenkins]
10.0.0.101

[gitlab]
10.0.0.102

[tomcat]
10.0.0.103
```

2> Install base
```
ansible-playbook site.yml --tags base
```

------------------------------------------------------
