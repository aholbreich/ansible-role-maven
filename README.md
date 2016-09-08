# Ansible Role: Acme 2.x

An Ansible role that installs Apache Maven on linux

## Requirements

Linux/Unix

## Role Variables

maven_version: 3.3.9 (Default)

## Dependencies

No hard dependencies for installation.

## Example Playbook

    - hosts: webservers
      roles:
        - { role: username.acme }

## License

MIT