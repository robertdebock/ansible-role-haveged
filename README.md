haveged
=========

[![Build Status](https://travis-ci.org/robertdebock/ansible-role-haveged.svg?branch=master)](https://travis-ci.org/robertdebock/ansible-role-haveged)

Provides haveged for your system.

Context
--------
This role is a part of many compatible roles. Have a look at [the documentation of these roles](https://robertdebock.nl/) for further information.

Here is an overview of related roles:
![dependencies](https://raw.githubusercontent.com/robertdebock/robertdebock.github.io/artifacts/haveged.png "Dependency")

Requirements
------------

A bootstrapped system, having Python and sudo.
Access to a repository containing the package haveged.

Role Variables
--------------

None known.

Dependencies
------------

You may use these roles to prepare your system.

- robertdebock.bootstrap
- robertdebock.epel

Download the dependencies by issuing this command:
```
ansible-galaxy install --role-file requirements.yml
```

Compatibility
-------------

This role has been tested against the following distributions and Ansible version:

|distribution|ansible 2.3|ansible 2.4|ansible 2.5|
|------------|-----------|-----------|-----------|
|alpine-3.6|yes|yes|yes|
|alpine-3.7|yes|yes|yes|
|archlinux|yes|yes|yes|
|centos-6|yes|yes|yes|
|centos-7|yes|yes|yes|
|debian-buster|yes|yes|yes|
|debian-jessie|yes|yes|yes|
|debian-stretch|yes|yes|yes|
|debian-wheezy|yes|yes|yes|
|fedora-27|yes|yes|yes|
|fedora-28|yes|yes|yes|
|opensuse-42.2|yes|yes|yes|
|opensuse-42.3|yes|yes|yes|
|ubuntu-artful|yes|yes|yes|
|ubuntu-bionic|yes|yes|yes|

Example Playbook
----------------

```
- hosts: servers

  roles:
    - role: robertdebock.bootstrap
    - role: robertdebock.epel
    - role: robertdebock.haveged
```

Install this role using `galaxy install robertdebock.haveged`.

License
-------

Apache License, Version 2.0

Author Information
------------------

Robert de Bock <robert@meinit.nl>
