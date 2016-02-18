# Ansible Fail2Ban Role
An ansible role for installing fail2ban.
This fork is to use iptables instead of firewalld to enable this role to be used in (CentOS in my case) instances running in OpenVZ.

[![Build Status](https://travis-ci.org/resmo/ansible-role-fail2ban.png?branch=master)](https://travis-ci.org/resmo/ansible-role-fail2ban)

## Usage:

    ---
    - hosts: all
      remote_user: root
      roles:
      - nimeshjm.fail2ban

## Homepage: 

https://github.com/nimeshjm/ansible-role-fail2ban
