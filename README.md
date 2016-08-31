Debian-SWMP
=============

A responsive, eye-pleasing Linux server statistics dashboard.

Requirements
------------

This role requires a debian compliant system such as ubuntu.

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: cowops.debian-swmp }

Tasks
-----

  - Install [swmp](https://swmp.thefuzz.xyz/)

License
-------

BSD
