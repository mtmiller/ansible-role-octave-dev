# Ansible Octave Development Environment Role

[![Build Status](https://travis-ci.org/mtmiller/ansible-role-octave-dev.svg?branch=master)](https://travis-ci.org/mtmiller/ansible-role-octave-dev)
[![Ansible Role](https://img.shields.io/ansible/role/21088.svg)](https://galaxy.ansible.com/mtmiller/octave-dev)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

This Ansible role installs all development tools and libraries needed to build
GNU Octave from source.

For now this role targets most releases of Debian and Ubuntu.

## Requirements

* Debian or Ubuntu target system
* Ansible 2.1 or greater

## Installation

Install this role from Ansible Galaxy with

    ansible-galaxy install mtmiller.octave-dev

## Example Playbook

This is an example playbook showing how to use this role.

    - hosts: servers
      roles:
         - mtmiller.octave-dev

## License

This role is licensed under the [MIT](https://opensource.org/licenses/MIT)
license. See [LICENSE.md](LICENSE.md) for the full license text.
