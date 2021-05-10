[![MIT License](https://raw.githubusercontent.com/roles-ansible/ansible_role_acmetool_debian_fix/main/.github/license.svg)](https://github.com/roles-ansible/ansible_role_acmetool_debian_fix/blob/main/LICENSE)
[![galaxy_acmetool](https://raw.githubusercontent.com/roles-ansible/ansible_role_acmetool_debian_fix/main/.github/galaxy.svg)](https://galaxy.ansible.com/do1jlr/acmetool_fix)

 ansible role acmetool_fix
==============================

Ansible role to install a acmetool from the URL defined in `defaults/main.yml`.

This is needed on debian buster *(debian10)*, because the acmetool release in the debian buster repos is to old.

We are using the debian sid *(debian testing)* repos.

This role is maintained until Debian Bullseye *(debian11)* is released and there is a more up to date version of acmetool.


This role is designed to work together with the [do1jlr.acmetool](https://github.com/roles-ansible/ansible_role_acmetool) role. But since it only install acmetool manually it will work on each debian based system, until debian bullseye is released.

 Testing
----------
This role is tested with [these github-action](https://github.com/search?q=topic%3Acheck-ansible+topic%3Agithub-actions+org%3Aroles-ansible&type=Repositories) tests for different versions of differen linux systems. Linting is tested via travis-ci and the  [ansible-lint action](https://github.com/marketplace/actions/ansible-lint).
If you want to find out more about our tests, please have a look at the github marketplace.

| test status | Github Marketplace |
| :---------  | :----------------  |
| [![Ansible Lint check](https://github.com/roles-ansible/ansible_role_acmetool_debian_fix/actions/workflows/ansible-linting-check.yml/badge.svg)](https://github.com/roles-ansible/ansible_role_acmetool_debian_fix/actions/workflows/ansible-linting-check.yml) | [ansible-lint action](https://github.com/marketplace/actions/ansible-lint) |
| [![Yamllint GitHub Actions](https://github.com/roles-ansible/ansible_role_acmetool_debian_fix/actions/workflows/yamllint.yaml/badge.svg)](https://github.com/roles-ansible/ansible_role_acmetool_debian_fix/actions/workflows/yamllint.yaml) |  [yamllint gitHub actions](https://github.com/marketplace/actions/yamllint-github-action) |
| | |
| [![Ansible check debian:stable](https://github.com/roles-ansible/ansible_role_acmetool_debian_fix/actions/workflows/ansible-debian-stable.yml/badge.svg)](https://github.com/roles-ansible/ansible_role_acmetool_debian_fix/actions/workflows/ansible-debian-stable.yml) | [ansible test with debian stable](https://github.com/marketplace/actions/check-ansible-debian-stable) |
| [![Ansible check debian:latest](https://github.com/roles-ansible/ansible_role_acmetool_debian_fix/actions/workflows/ansible-debian-latest.yml/badge.svg)](https://github.com/roles-ansible/ansible_role_acmetool_debian_fix/actions/workflows/ansible-debian-latest.yml) | [ansible test with debian latest](https://github.com/marketplace/actions/check-ansible-debian-latest) |
| [![Ansible check debian:sid](https://github.com/roles-ansible/ansible_role_acmetool_debian_fix/actions/workflows/ansible-debian-sid.yml/badge.svg)](https://github.com/roles-ansible/ansible_role_acmetool_debian_fix/actions/workflows/ansible-debian-sid.yml) | [ansible test with debian sid](https://github.com/marketplace/actions/check-ansible-debian-sid) |
| [![Ansible check debian:buster](https://github.com/roles-ansible/ansible_role_acmetool_debian_fix/actions/workflows/ansible-debian-buster.yml/badge.svg)](https://github.com/roles-ansible/ansible_role_acmetool_debian_fix/actions/workflows/ansible-debian-buster.yml) | [ansible test with debian buster](https://github.com/marketplace/actions/check-ansible-debian-buster) |
| [![Ansible check debian:stretch](https://github.com/roles-ansible/ansible_role_acmetool_debian_fix/actions/workflows/ansible-debian-stretch.yml/badge.svg)](https://github.com/roles-ansible/ansible_role_acmetool_debian_fix/actions/workflows/ansible-debian-stretch.yml) | [ansible test with debian stretch](https://github.com/marketplace/actions/check-ansible-debian-stretch) |
