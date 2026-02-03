Ansible role: Template
=========

[![CI](https://github.com/xiple/ansible-role-template/actions/workflows/ci.yml/badge.svg)](https://github.com/xiple/ansible-role-template/actions/workflows/ci.yml)

An ansible template role. Use it to scaffold ansible roles.

Requirements
----------------

None.

Role Variables
----------------

None.

Supported distributions
----------------

This role has been been developed and tested on the following distributions :

- Debian : 13
- Fedora : 43, 42

Example Playbook
----------------

```yaml
- hosts: all
  roles:
    - xiple.template
```

License
-------

MIT
