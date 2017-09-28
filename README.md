Role Name
=========
amq7

Requirements
------------
This role expects that you already have a tarball or zip of an activemq 7 installation located in the 'files' dir.  You will need to update the 'defaults/main.yml' with the exact tarball/zip name

Role Variables
--------------
defaults/main.yml

Example Playbook
----------------

    - hosts: servers
      roles:
         - amq7

License
-------

BSD

Author Information
------------------
ky13 -- kritchie@redhat.com
