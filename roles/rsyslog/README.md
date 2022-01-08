Role Name
=========

rsyslog 

You must change user attributes (name and home path) in group_vars/all 
```bash
---
user:
  name: change_me
  home: /home/change_me
```
or create a file in ryslog/vars/main.yaml :
```bash
user:
  name: you
  home: /home/you
```

Requirements
------------

- Ansible
- systemd

