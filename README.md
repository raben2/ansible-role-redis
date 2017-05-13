Ansible Role: Redis
===================

Install a redis server from source and run as systemd daemon

## Requirements

None.

## Role Variables

Please refer to defaults/main.yml for individual configuration

## Dependencies

None.

## Example Playbook
```yaml
    - hosts: server
      roles:
        - { role: raben2.redis }
```
## License

LGPL

## Author Information

This role was created in 2017 by [Georg Rabenstein](https://github.com/raben2)