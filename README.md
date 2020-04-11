![Ansible Lint](https://github.com/johanneskastl/ansible-role-install_nfsserver_packages/workflows/Ansible%20Lint/badge.svg)

install_nfsserver_packages
=========

Install packages required to run a NFS server.

Requirements
------------

None.

Role Variables
--------------

`nfsserver_packages`: List of packages to install.

Dependencies
------------

None.

Example Playbook
----------------


    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD-3-Clause

Author Information
------------------

I am Johannes Kastl, reachable via kastl@b1-systems.de.
