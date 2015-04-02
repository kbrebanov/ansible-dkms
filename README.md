dkms
====

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
