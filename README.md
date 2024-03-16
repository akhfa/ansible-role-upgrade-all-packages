[![CI tests](https://github.com/akhfa/ansible-role-upgrade-all-packages/actions/workflows/ci_tests.yml/badge.svg)](https://github.com/akhfa/ansible-role-upgrade-all-packages/actions/workflows/ci_tests.yml)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-akhfa.upgrade_all_packages-blue.svg)](https://galaxy.ansible.com/akhfa/upgrade_all_packages)


ansible-role-upgrade-all-packages
=========

Upgrade all packages. Optionally reboot the system if a new kernel was installed.

The default is to reboot when a new kernel is installed unless you define `upgrade_all_packages_kernel_reboot: false`

*This role is not idempotent*

Role Variables
--------------

```
upgrade_all_packages_reboot: true
```

Dependencies
------------

none

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: akhfa.upgrade_all_packages }

License
-------

GPLv3

Author Information
------------------

Initial Author: Pablo Escobar Lopez [<img src="https://edent.github.io/SuperTinyIcons/images/svg/github.svg" width="20" />](https://github.com/pescobar/)

Current Maintainer: Akhmad Fakhoni Listiyan Dede [<img src="https://edent.github.io/SuperTinyIcons/images/svg/github.svg" width="20" />](https://github.com/akhfa/) [<img src="https://edent.github.io/SuperTinyIcons/images/svg/linkedin.svg" width="20" title="LinkedIn">](https://www.linkedin.com/in/akhmadfakhoni/)