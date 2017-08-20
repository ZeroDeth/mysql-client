MySQL Client
=========

Ansible role to install mysql client.

Requirements
------------

- Ubuntu 16.04
- Ansible 1.9

Role Variables
--------------

```
mysql_client_install_client: true
mysql_client_install_libraries: true
```

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - { role: zerodeth.mysql-client }

License
-------

BSD

Author Information
------------------

This role was created in 2017 by ZeroDeth
