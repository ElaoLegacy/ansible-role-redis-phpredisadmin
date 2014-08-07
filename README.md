Ansible Role - PhpRedisAdmin
============================

A phpRedisAdmin role to install phpRedisAdmin on elao symfony standard vagrant box

Requirements
------------

This role only run on elao symfony standard vagrant box. See https://vagrantcloud.com/elao/symfony-standard-debian

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: elao.redis-phpredisadmin }

License
-------

MIT

Author Information
------------------

http://www.elao.com/
