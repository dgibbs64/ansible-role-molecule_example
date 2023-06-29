# molecule_example

An example [Ansible](https://www.ansible.com) role for testing Molecule.

## About

This role is an example of how to use Molecule to test an Ansible role.

## Requirements

None.

## Role Variables

None.

## Dependencies

None.

## Example Playbook

```yaml
---
- name: Linux Admin Packages
  hosts: all
  roles:
    - role: "dgibbs64.molecule_example"
```

## License

MIT

## Author Information

- [Daniel Gibbs](https://danielgibbs.co.uk)
