# ansible-apps_vmwaretools

[![Galaxy Role](https://img.shields.io/badge/galaxy-apps_vmwaretools-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/apps_vmwaretools)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-apps_vmwaretools.svg)](https://github.com/lotusnoir/ansible-apps_vmwaretools/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-apps_vmwaretools?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/apps_vmwaretools)
[![downloads](https://img.shields.io/ansible/role/d/)](https://galaxy.ansible.com/lotusnoir/apps_vmwaretools)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/)](https://galaxy.ansible.com/lotusnoir/apps_vmwaretools)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [Description](#description)
- [Requirements](#requirements)
- [Role variables](#role-variables)
- [Examples](#examples)
- [License](#license)
- [Author Information](#author-information)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Description

Install and configure vmware tools

## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: apps_vmwaretools
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-apps_vmwaretools

## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

## Author Information

- [Philippe LEAL](https://github.com/lotusnoir)
