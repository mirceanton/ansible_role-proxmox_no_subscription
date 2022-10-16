Proxmox: No Subscription
========================

An Ansible Role that automatically configures the apt repos for a Proxmox VE server that is running with no subscription.

Requirements
------------

N/A.

Role Variables
--------------

N/A.

For more details about the **default** variables, take a look at the [defaults/main.yml](defaults/main.yml).

Dependencies
------------

N/A.

Example Playbook
----------------

``` yml
---
- name: Set up repositories on all PVE hosts
  hosts: pve
  remote_user: root

  roles:
    - role: mirceanton.proxmox_no_subscription
```

MIT

Author Information
------------------

A role developed by [Mircea-Pavel ANTON](https://www.mirceanton.com).
