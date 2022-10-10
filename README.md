# sia-playbook
Uses Ansible to setup a Sia daemon on a machine, as well as useful tools for managing it.

This playbook aims to be idempotent, repeatable and self-contained, setting everything up under ~siad.

## Usage
Edit `inventory`, placing your host(s) into the [sia] hostgroup, edit the settings in `site.yml` then run

`ansible-playbook site.yml`
