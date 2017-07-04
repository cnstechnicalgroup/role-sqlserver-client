Role: cnstechnicalgroup.sqlserver-client
========

Ansible role install sqlcmd

Requirements
------------

* CentOS7 
* Ubuntu Xenial Xenus


Dependencies
------------

This package has no dependencies.

License
-------

GPLv2

Author Information
------------------

Created by CNS Technical Group (https://www.cnstechgroup.com/)


Documentation
------------------

Install example (https://github.com/cnstechnicalgroup/ansible-sqlserver/blob/master/documents/sqlserver_client_install.md)

Examples
--------

```yaml
---
- name: cnstechnicalgroup.sqlserver-client role 
  hosts: dbclients
  sudo: no
  roles: 
  - cnstechnicalgroup.sqlserver-client
  gather_facts: yes
  environment:
    target_home: "{{target_home}}"
    ACCEPT_EULA: "Y"

```
