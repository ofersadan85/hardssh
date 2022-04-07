# hardssh

This ansible role will harden ssh settings (both client and server)

## Install

    ansible-galaxy role install ofersadan85.hardssh

## Example Playbook

This is a simple role without variables

    - hosts: servers
      roles:
        - ofersadan85.hardssh
