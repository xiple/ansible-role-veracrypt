Ansible role: Veracrypt
=========

[![CI](https://github.com/xiple/ansible-role-veracrypt/actions/workflows/ci.yml/badge.svg)](https://github.com/xiple/ansible-role-veracrypt/actions/workflows/ci.yml)

An ansible role to install Veracrypt.

Requirements
----------------

None.

Role Variables
----------------

```yaml
veracrypt_version: 1.26.24
```

The veracrypt version to be installed.

See `defaults/main.yml` for all configurable values.

Supported distributions
----------------

This role has been been developed and tested on the following distributions :

- Ubuntu : 24.04
- Debian : 13
- Fedora : 43, 42 (use Veracrypt Fedora 40 RPM file)

Example Playbook
----------------

```yaml
- hosts: all
  roles:
    - xiple.veracrypt
```

License
-------

MIT
