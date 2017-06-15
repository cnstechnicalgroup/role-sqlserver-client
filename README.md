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
- name: cns.sqlserver-client role 
  hosts: dbclient
  sudo: yes
  roles: 
  - cns.sqlserver-client
  gather_facts: no

```
