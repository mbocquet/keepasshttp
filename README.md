# keepasshttp

Ansible role to install dependencies and libs to run the KeepassHttp plugin
under Keepass2 (see http://keepass.info/).

## Requirements

Keepass2.

## Role Variables

None.

## Dependencies

None.

## Install this role as submodule of an existing GIT repository

`git submodule add https://git.sekoya.org/mb/keepasshttp.git roles/keepasshttp`

## Example Playbook

    - hosts: workstations
      roles:
         - keepasshttp

or

    - hosts: workstations
      roles:
         - { role: keepasshttp, x: 42 }

if any variables comes in the future fot this role.

## License

GPLv3

## Author Information

http://www.sekoya.org
