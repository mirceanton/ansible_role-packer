Ansible Role: Packer
====================

An Ansible role that installs Packer by configuring the apt repo.

Requirements
------------

N/A

Role Variables
--------------

This role has no customizable variables.

To check the default variables, take a look at the [defaults](defaults/main.yml) file.

Dependencies
------------

N/A

Example Playbook
----------------

``` yml
---
- hosts: all
  remote_user: root

  roles:
    - role: mirceanton.packer
```

License
-------

MIT

Author Information
------------------

A role developed by [Mircea-Pavel ANTON](https://www.mirceanton.com).
