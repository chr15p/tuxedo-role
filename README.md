Role Name
=========

A simple role to install BEA/Oracle tuxedo server as the tuxedo user

Requirements
------------
You need the tuxedo software as a zip file either on a webserver accessable by the target or as a file://

Role Variables
--------------

* tuxedo_url  - the URL (including filename) to find the tuxedo zip file

Dependencies
------------

No external dependancies

Example Playbook
----------------

- hosts: tuxedoservers
  vars:   
          tuxedo_url: http://192.168.122.1:8080/tuxedo122200_64_Linux_01_x86.zip
  roles:
    - tuxedo


License
-------

GPLv2

Author Information
------------------

https://github.com/chr15p/
