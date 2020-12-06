Ansible role : bootstrap
========================

Install packages that I commonly install.
By default, for security reasons the environment variables are removed by `sudo` command.
I usually want to keep ssh agents forwarding active, when I work as a super user.
So this role adds SSH_AUTH_SOCK to default env_keep in `/etc/sudoers.d/auth_socket`
In the past I used to `/etc/sudoers`, so the role remove the line from this file.

Requirements
------------

CentOS 7 or CentOS 8

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

    molecule test

License
-------

[WTFPL](https://raw.githubusercontent.com/hxpro/ansible-role-bootstrap/master/LICENSE)

Author Information
------------------

Matěj Koudelka <matej@hxpro.cz>
