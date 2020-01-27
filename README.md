# Ansible Role: haproxy
=========

A simple Ansible role for installing and configuring the MariaDB, Apache and WordPress for RHEL/CentOS 7 and Debian 10.

Install the necessary packages;
Create configuration file;


Requirements
------------

- The SELinux and firewall settings are not considered to be a concern of this role.

Role Variables
--------------


Variables below are required

| Variable                                     | Default                       | Comments                                     
| :---                                         | :---                          | :---       
|                                              |                               |
| `mariadb_user_root`                          | root                          |
|                                              |                               |
| `mariadb_root_password`                      |                               | Inform root password
|                                              |                               |


Dependencies
------------

You need to install python-apt package on debian 10 


Example Playbook
----------------

---
- hosts: mariadb_server

  roles:

    - /path/mariadb

...

## Contributing

Issues, feature requests, ideas are appreciated and can be posted in the Issues section.


Author Information
------------------
LinkedIn: https://br.linkedin.com/in/almircandido
