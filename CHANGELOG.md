# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.1.0](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_vmwaretools/compare/1.0.0...1.1.0) - 2025-10-10

### Commits

- add support for ubuntu24 [`fefab89`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_vmwaretools/commit/fefab891de587b1a858f5ea1870af998adf46662)
- add version on molecule play image to maintain support on old release [`4c53fa6`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_vmwaretools/commit/4c53fa6212c2aaa37b60fe5784d0da1c6a07cbaf)
- remove support for debian10 / ubuntu18 / redhat8 [`b5db616`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_vmwaretools/commit/b5db61654645cdb32dff166d457f6e2e9bf31931)
- update molecule [`db35759`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_vmwaretools/commit/db357593698d69d9d2eaa0534e588341100b0062)
- add redhat 9 to default supported distrib [`ef56f23`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_vmwaretools/commit/ef56f23d4828a16d2fe9bb6e1d8ede3e69562b16)
- add redhat 8 to default supported distrib [`dcd63aa`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_vmwaretools/commit/dcd63aabdc78a9033de307b30f11ba3708f7914c)
- sort testing distrib to avoid random changes [`2e10487`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_vmwaretools/commit/2e104872ecb0fef29d26d6a23a8b9b5a9213090c)
- update pre-commit and lint fix [`9a26a39`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_vmwaretools/commit/9a26a39effc4b0e8d191322fb6a88d38cd231878)
- remove support for rhel7 and docker dind on gitlab [`5527b83`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_vmwaretools/commit/5527b83868d4190457c0fc871c648e467c07cba8)
- remove lint from pipeline [`fe60d8c`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_vmwaretools/commit/fe60d8c28aa0740c12262051902e7926ad43ffd3)

## [1.0.0](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_vmwaretools/compare/0.1.0...1.0.0) - 2025-10-10

### Commits

- clean + upgrade vars [`fe9384c`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_vmwaretools/commit/fe9384cf02cc7866c76d2e697641d00e7f7f7137)
- fix service name on rhel [`52e1f64`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_vmwaretools/commit/52e1f645056c96eb9cc1c9923da44a6878873437)
- update vars [`0c16260`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_vmwaretools/commit/0c162603af3d20acefdc90cb1167169be9bd5ab0)
- update readme + precommit + include vars [`f9e2cff`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_vmwaretools/commit/f9e2cff0fc3547fd1fb2ed637bb833df0c8f840f)
- add ansible comment on template files + change install module to minimize tasks [`90b16e6`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_vmwaretools/commit/90b16e695f83f3a60afd51ffc23f1758f902360d)
- update molecule playbook order and main include vars [`430de9d`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_vmwaretools/commit/430de9dbfe6963af259757222d5f54c032d728ed)
- fix config tasks that are played even if vm not on vmware [`7ce0acf`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_vmwaretools/commit/7ce0acf4ce20551adc91e0f8d5b324586c92baed)

## 0.1.0 - 2025-10-10

### Commits

- add debian12 support [`fc8db37`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_vmwaretools/commit/fc8db37a9ed585f6e72719c24fdcf8a4a3427713)
- fix template [`85cef86`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_vmwaretools/commit/85cef86837f2dbfd4ebbab620ce965cfdef3a3d8)
- initial commit [`d2e0105`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_vmwaretools/commit/d2e0105310391ee7a03e50cdbbda301ee4963695)
