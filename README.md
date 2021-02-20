Git ansible role
================

![CI](https://github.com/baztian/ansible-git/workflows/CI/badge.svg)

Role to download, install and setup git plus associated tools.

Example Playbook
----------------

    - hosts: servers
      become: yes
      roles:
         - role: baztian.git

License
-------

MIT
