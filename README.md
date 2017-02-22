# Ansible Role: Supervisor

[![Build Status](https://travis-ci.org/gikoluo/ansible-role-supervisor.svg?branch=master)](https://travis-ci.org/gikoluo/ansible-role-supervisor)

Installs Supervisor (latest)

## Supported platforms

```
CentOS 6 & 7
RedHat 6
Ubuntu 14.04
```

## Requirements

None

## Role Variables

None

## Dependencies

```
```

## Example Playbook

```
- hosts: servers
  roles:
    - { role: gikoluo.supervisor }
```

```
ansible-playbook samples/supervisor.yaml -i vagrant -l "*.106"
```

## License

MIT

## Author Information

Created by [Giko Luo](https://github.com/gikoluo)

