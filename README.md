# Ansible Role: GNU Mirror

Installs the GNU mirroring role

## Requirements

None.

## Role Variables

See `defaults/main.yml`.

## Dependencies

nexcess.mirror

## Add to Requirements

    - src: https://github.com/nexcess/ansible-role-gnu-mirror.git
      name: nexcess.gnu-mirror

## Example Playbook

    - hosts: servers
      roles:
        - nexcess.gnu-mirror

## License

MIT / BSD
