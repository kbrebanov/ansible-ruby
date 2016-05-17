ruby
====

[![Ansible Role](https://img.shields.io/ansible/role/3932.svg)](https://galaxy.ansible.com/list#/roles/3932)

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
