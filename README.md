Role Name
=========

systemd-resolved Install and setup on archlinux
NOTE: this role will remove openresolv and mask avahi-daemon if it esists

Requirements
------------

NO

Role Variables
--------------

NO

Dependencies
------------

NO

Example Playbook
----------------

- hosts: localhost
  remote_user: root
  roles:
    - systemd-resolved-archlinux

License
-------

MIT

Author Information
------------------

©deviousway
