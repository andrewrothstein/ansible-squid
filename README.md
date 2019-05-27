andrewrothstein.squid
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-squid.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-squid)

Installs [Squid](http://www.squid-cache.org/)

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.squid
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
