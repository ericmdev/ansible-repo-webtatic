# Ansible Role: Webtatic Repository

Installs Webtatic repository (containing updated web-related packages).

## Requirements

- RHEL/CentOS

## Dependencies

None.

## Example Playbook

    - hosts: servers
      roles:
        - { role: ansibles.repo-webtatic }