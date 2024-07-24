# Ansible Role: Update OS

[![CI](https://github.com/geerlingguy/ansible-role-postgresql/workflows/CI/badge.svg?event=push)](https://github.com/geerlingguy/ansible-role-postgresql/actions?query=workflow%3ACI)
Role for updating the OS

## Requirements

No special requirements; note that this role requires root access, so either run it in a playbook with a global `become: yes`, or invoke the role in your playbook like in the Example:

## Role Variables

## Dependencies

None.

## Example Playbook

    - hosts: all
      become: yes
      roles:
        - role-os_update

## License

MIT / BSD

## Author Information

This role was created in 2024 by lokcal
