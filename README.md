[![No Maintenance Intended](http://unmaintained.tech/badge.svg)](http://unmaintained.tech/)

thruk
=====

Installs and configures Thruk.

Requirements
------------

This role requires Ansible 1.6 or higher.

Role Variables
--------------

| Name          | Default | Description                  |
|---------------|---------|------------------------------|
| thruk_version | 2.05    | Version of Thruk to install  |

Dependencies
------------

None

Example Playbook
----------------

Install Thruk
```
- hosts: all
  roles:
      - kbrebanov.thruk
```

License
-------

BSD

Author Information
------------------

Kevin Brebanov
