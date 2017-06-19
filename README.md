Role: cnstechnicalgroup.sqlserver-client
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
- name: cnstechnicalgroup.sqlserver-client role 
  hosts: dbclients
  sudo: yes
  roles: 
  - cnstechnicalgroup.sqlserver-client
  gather_facts: no

```
