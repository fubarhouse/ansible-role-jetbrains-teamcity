# Ansible Role: TeamCity

[![Build Status](https://img.shields.io/travis/fubarhouse/ansible-role-jetbrains-teamcity/master.svg?style=for-the-badge)](https://travis-ci.org/fubarhouse/ansible-role-jetbrains-teamcity)
[![stability-stable](https://img.shields.io/badge/stability-stable-green.svg?style=for-the-badge)](https://github.com/orangemug/stability-badges)
[![Ansible Galaxy](https://img.shields.io/ansible/role/14002.svg?style=for-the-badge)](https://galaxy.ansible.com/fubarhouse/jetbrains-teamcity)
[![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg?style=for-the-badge)](https://raw.githubusercontent.com/fubarhouse/ansible-role-teamcity/master/LICENSE)

* Installs Java v7 on Ubuntu servers
* Installs MySQL on Ubuntu servers
* Installs Jetbrains' TeamCity on Ubuntu servers

## Preview
![screenshot](https://raw.githubusercontent.com/fubarhouse/ansible-role-teamcity/master/images/login-screen.png)

## Requirements

  Java 8 or later.

## Role Variables

    teamcity_domain: teamcity.vagrant.dev
    teamcity_version: 10.0.1
    teamcity_db_user: teamcity
    teamcity_db_passw: 12345

## Dependencies

  Dependencies are checked off as the role installs.

## Installation

  * Add the role to your playbook.
  * Modify above variables as desired.

## License

MIT / BSD

## Author Information

This role was created in 2016 by [Karl Hepworth](https://twitter.com/fubarhouse).

This role was created due to having unavailable options of success. It was created because I failed to get the galaxy role [sa-teamcity](https://github.com/softasap/sa-teamcity) to work correctly or test correctly. I hope it helps others.

