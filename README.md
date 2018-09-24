[![No Maintenance Intended](http://unmaintained.tech/badge.svg)](http://unmaintained.tech/)

ruby
====

[![Build Status](https://travis-ci.org/kbrebanov/ansible-ruby.svg?branch=master)](https://travis-ci.org/kbrebanov/ansible-ruby)

Installs Ruby

Requirements
------------

This role requires Ansible 1.9 or higher.

Role Variables
--------------

| Name         | Default | Description                |
|:-------------|:--------|:---------------------------|
| ruby_version | 2.3.1   | Version of Ruby to install |

Dependencies
------------

- kbrebanov.git

Example Playbook
----------------


Install Ruby
```yaml
- hosts: all
  roles:
    - kbrebanov.ruby
```

Install older version of Ruby
```yaml
- hosts: all
  vars:
    ruby_version: 2.2.1
  roles:
    - kbrebanov.ruby
```

License
-------

BSD

Author Information
------------------

Kevin Brebanov
