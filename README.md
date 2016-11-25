Beanstalkd
========

[![Build Status](https://travis-ci.org/vpeltot/beanstalkd.svg?branch=master)](https://travis-ci.org/vpeltot/beanstalkd)

Install beanstalkd

Requirements
------------

none


Role Variables
--------------

| Variable name                           | Description          | Default value   |
|-----------------------------------------|----------------------|-----------------|
| `beanstalkd_listen_address`             | Listen on address    | 127.0.0.1       |
| `beanstalkd_listen_port`                | Listen on port       | 11300           |

Example Playbook
-------------------------

    - hosts: servers
      roles:
         - { role: vpeltot.beanstalkd }

License
-------

MIT