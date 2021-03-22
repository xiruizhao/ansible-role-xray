# Set up xray client/server on Debian/Ubuntu
1. Install `ansible-galaxy install git+https://github.com/xiruizhao/ansible-role-xray.git`
2. Usage
```yaml
---
- hosts: all
  become: yes
  roles:
    - role: ansible-role-xray
      xray_server_addr: example.com
```
