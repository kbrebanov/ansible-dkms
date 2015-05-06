dkms
====

Installs DKMS.

[![Ansible Galaxy](https://img.shields.io/badge/galaxy-kbrebanov.dkms-660198.svg)](https://galaxy.ansible.com/list#/roles/3291)

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
