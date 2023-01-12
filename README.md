# hardssh

This ansible role will harden ssh settings (both client and server).
Test your SSH security settings with [https://www.sshaudit.com/](https://www.sshaudit.com/), the goal of this role is to always comply with a 100/100 score!

## Install

    ansible-galaxy role install ofersadan85.hardssh

## Example Playbook

This is a simple role without variables

    - hosts: servers
      roles:
        - ofersadan85.hardssh

## Local run

To run it locally on your machine

    ansible localhost -m include_role -a name=ofersadan85.hardssh --become -K  # Remove `-K` if your user does not need a password to sudo
