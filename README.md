Generic hostname setup ansible role
==============================

This Ansible role setup hostname of target hosts according to `ansible_inventory_name` variable

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: all
  roles:
    - generic.hostname-to-inventoryname-setup
```

License
-------

MIT

Author Information
------------------

Andrey Makarov <mb@mcrrw.me>
