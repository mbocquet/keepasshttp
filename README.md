# keepasshttp

Install dependencies and libs to run KeepassHttp plugin into Keepass2 (see http://keepass.info/).

## Requirements

Keepass2.

## Role Variables

None.

## Dependencies

None.

## Example Playbook

    - hosts: workstations
      roles:
         - mbocquet.keepasshttp

or

    - hosts: workstations
      roles:
         - { role: mbocquet.keepasshttp, x: 42 }

if any variables comes in the future fot this role.

## License

GPLv3

## Author Information

http://www.sekoya.org
