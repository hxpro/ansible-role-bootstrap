hxpro.bootstrap
===============

Bootstrap common stuff.

Requirements
------------

CentOS

Role Variables
--------------

no role variables

Dependencies
------------

 - hxpro.epel - install epel repository

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: hxpro.bootstrap }

Testing
-------

Test require docker on your localhost

    ansible-galaxy install -r requirements.yml
    ansible-playbook test.yml

License
-------

[WTFPL](https://raw.githubusercontent.com/hxpro/ansible-role-bootstrap/master/LICENSE)

Author Information
------------------

Matěj Koudelka <matej@hxpro.cz>
