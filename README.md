hxpro.mongodb
=============

MongoDB

Role Variables
--------------

    mongodb_bind_ip: 127.0.0.1
    mongodb_port: 27017

Dependencies
------------

 - hxpro.epel

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: mongodb
           mongodb_bind_ip: 127.0.0.1
           mongodb_port: 27017

License
-------

WTFPL

Author Information
------------------

Matěj Koudelka <matej@hxpro.cz>
