# Ansible Role: Webtatic Repository

Installs Webtatic repository (containing updated web-related packages).

## Requirements

- EL/Enterprise Linux (RHEL/CentOS) - Version 6

## Dependencies

None.

## Example Playbook

    - hosts: servers
      roles:
        - { role: ansibles.repo-webtatic }