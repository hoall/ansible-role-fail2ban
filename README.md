# Role fail2ban

Installs fail2ban from the epel 7 release repository and configures a jail for ssh.

NOTE:
The role enables the epel 7 release to do is actual job. If you don't want this, rewrite the role.

## Requirements

## Role Variables

## Dependencies

none

## Example Playbook

    - hosts: servers
      roles:
         - { role: hoall.fail2ban }

## License

BSD-2-Clause

## Author Information

Felix Paetow fhmpaetow@fsfe.org

