Role Nginx
=========

Requirements
------------
Для установки роли создайте 'requirements.yml'
```
  - name: nginx_role
    src: git@github.com/chernykhal/nginx-role.git
    scm: git
    version: "[last version]"
```

Role Variables
--------------
[defaults/main.yml](./defaults/main.yml) - изменяемые параметры;

Example usage:
----------------
```
- name: Install nginx
  hosts: [host]
  roles:
    - nginx_role
```
-------


