# dhcpd

[![Ansible Role](https://img.shields.io/ansible/role/d/58170)](https://galaxy.ansible.com/volker_raschek/dhcpd)

With following role can be dhcpd installed and configured.

## Installation

```bash
ansible-galaxy install volker_raschek.dhcpd
```

## Supported distributions

- Arch Linux
- Rocky Linux 8
- Ubuntu 20.04

## Features

- Installing dhcpd
- Configuring dhcpd
  - TSIG-Keys
  - Simple Zones
  - Multiple subnets listen on different interfaces
  - DYNDNS

## Configuring

In the default directory are examples how to configure `dhcpd`. Copy the
defaults into your `host_vars` or `group_vars` and adapt the examples.
