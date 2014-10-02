jorti.mariadb
=========

MariaDB role for Fedora and CentOS >= 7

Role Variables
--------------


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: jorti.mariadb, mariadb_open_firewall: true, mariadb_remote_root_access: false }

License
-------

GPLv3

Author Information
------------------

https://miceliux.com/apuntesderoot/about/
