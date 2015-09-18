dkms
====

[![Ansible Role](https://img.shields.io/ansible/role/3291.svg)](https://galaxy.ansible.com/list#/roles/3291)

Installs DKMS.

Requirements
------------

This role requires Ansible 1.4 or higher.

Role Variables
--------------

None

Dependencies
------------

CentOS:
  - kbrebanov.epel

Example Playbook
----------------

Install DKMS
```
  - hosts: all
    roles:
      - { role: dkms }
```

License
-------

BSD

Author Information
------------------

Kevin Brebanov
