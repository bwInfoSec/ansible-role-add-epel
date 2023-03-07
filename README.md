![Molecule Test](https://github.com/bwinfosec/ansible-role-add-epel/actions/workflows/molecule-test.yml/badge.svg)

ansible-role-add-epel
=========

This role adds the [EPEL](https://www.redhat.com/en/blog/whats-epel-and-how-do-i-use-it) repository to RHEL.

## Platforms

- RHEL 8

## Example Playbook

```yml
    - hosts: rhel
      roles:
         - { role: bwinfosec.add_epel }
```

## Local Development

This role includes a *molecule* test to execute on RHEL 8.

## Licensing

This work is licensed under the [EUPL 1.2](https://joinup.ec.europa.eu/collection/eupl/eupl-text-eupl-12).

## Contribution
If you want to contribute feel free to do so by creating a pull request on [github](https://github.com/bwInfoSec/ansible-role-add-epel).