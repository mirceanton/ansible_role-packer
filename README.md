Ansible Role: Packer
=======================

An Ansible role that installs Packer by downloading the precompiled binary.

Requirements
------------

N/A

Role Variables
--------------

|       Variable        |  Type  | Default |                 Description                  |
| :-------------------: | :----: | :-----: | :------------------------------------------: |
|   `packer_version`    | string | `1.8.4` |      The version of packer to install.       |
| `packer_architecture` | string | `amd64` | The architecture for the binary to download. |
|      `packer_os`      | string | `linux` |      The OS for the binary to download.      |

For more details about the **default** variables, take a look at the [defaults/main.yml](defaults/main.yml).

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
      vars:
        packer_version: "1.8.4"
        packer_architecture: arm64
        packer_os: linux
```

License
-------

MIT

Author Information
------------------

A role developed by [Mircea-Pavel ANTON](https://www.mirceanton.com).
