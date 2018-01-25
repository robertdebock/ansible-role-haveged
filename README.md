haveged
=========

[![Build Status](https://travis-ci.org/robertdebock/ansible-role-haveged.svg?branch=master)](https://travis-ci.org/robertdebock/ansible-role-haveged)

Provides haveged for your system.

Requirements
------------

A bootstrapped system, having Python and sudo.
Access to a repository containing the package haveged.

Role Variables
--------------

None known.

Dependencies
------------

- robertdebock.bootstrap

Download the dependencies by issuing this command:
```
ansible-galaxy install --role-file requirements.yml
```

Example Playbook
----------------

```
- hosts: servers

  roles:
    - role: robertdebock.haveged
```

Install this role using `galaxy install robertdebock.haveged`.

License
-------

Apache License, Version 2.0

Author Information
------------------

Robert de Bock <robert@meinit.nl>
