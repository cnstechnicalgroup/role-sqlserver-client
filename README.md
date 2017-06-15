Role: cns.sqlserver-client
========

Ansible role install sqlcmd

Requirements
------------

* CentOS7 

Dependencies
------------

This package has no dependencies.

License
-------

GPLv2

Author Information
------------------

Created by CNS Technical Group (https://www.cnstechgroup.com/)

Examples
--------

```yaml
---
- name: role.sqlserver-client role 
  hosts: dbservers
  sudo: yes
  roles: 
  - cns.sqlserver-client
  gather_facts: no

```
