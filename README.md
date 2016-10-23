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

    cd tests
    ansible-galaxy install -r requirements.yml
    ansible-playbook test.yml

License
-------

[WTFPL](https://raw.githubusercontent.com/hxpro/ansible-role-bootstrap/master/LICENSE)

Author Information
------------------

Ansible novice
