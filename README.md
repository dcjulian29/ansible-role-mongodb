# Ansible Role: mongodb

[![Lint](https://github.com/dcjulian29/ansible-role-mongodb/actions/workflows/lint.yml/badge.svg)](https://github.com/dcjulian29/ansible-role-mongodb/actions/workflows/lint.yml) [![GitHub Issues](https://img.shields.io/github/issues-raw/dcjulian29/ansible-role-mongodb.svg)](https://github.com/dcjulian29/ansible-role-mongodb/issues)

This an Ansible role to install MongoDB Community Server.

## Requirements

- Active Internet Connection.

## Installation

To use, use `requirements.yml` with the following git source:

```yaml
---
roles:
- name: dcjulian29.mongodb
  src: https://github.com/dcjulian29/ansible-role-mongodb.git
  ```

Then download it with `ansible-galaxy`:

```shell
ansible-galaxy install -r requirements.yml
```

## Dependencies

- None
