[![Build Status](https://travis-ci.org/wtanaka/ansible-role-slack.svg?branch=master)](https://travis-ci.org/wtanaka/ansible-role-slack)
[![CircleCI](https://circleci.com/gh/wtanaka/ansible-role-slack.svg?style=svg)](https://circleci.com/gh/wtanaka/ansible-role-slack)

wtanaka.slack
==============

Ansible role to install slack desktop client

Example Playbook
-------------------------

    - hosts: all
      roles:
         - wtanaka.slack

### `slack_version`

The version of slack to install, e.g. `slack_version: 2.5.2`


The full set of configuration options available are visible in
[defaults/main.yml](defaults/main.yml)

License
-------

GPLv2

Author Information
------------------

http://wtanaka.com/
