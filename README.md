# Ansible Role - Docker Python Pip

[![Build Status](https://travis-ci.org/elnebuloso/ansible-role-docker-pip.svg?branch=master)](https://travis-ci.org/elnebuloso/ansible-role-docker-pip)

## Requirements

This role requires Ansible 2.0 or higher, and platform requirements are listed in the metadata file.

## Supported Distributions

- ubuntu14
- ubuntu16

## Role Variables

- [`defaults/main.yml`](https://github.com/elnebuloso/ansible-role-docker-pip/blob/master/defaults/main.yml)

## Example Playbook

```
- hosts: localhost
  roles:
    - role: elnebuloso.docker-pip
```

## Dependencies

None.

##  License

MIT

##  Author Information

This role was created in 2016 by [elnebuloso](https://github.com/elnebuloso/)