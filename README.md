Proxmox: No Subscription
========================

An Ansible Role that automatically configures a Proxmox VE server that is running with no subscription.

Requirements
------------

N/A.

Role Variables
--------------

|   Variable    | Default |                      Description                      |
| :-----------: | :-----: | :---------------------------------------------------: |
| `disable_nag` | `true`  | whether or not to disable the "no subscription" popup |
|   `upgrade`   | `true`  |      whether or not to run an `apt dist-upgrade`      |
|   `reboot`    | `true`  |    whether or not to reboot at the end of the role    |

Dependencies
------------

N/A.

Example Playbook
----------------

``` yml
---
- hosts: all
  remote_user: root

  roles:
    - role: mirceanton.proxmox_nosub
```

MIT

Author Information
------------------

A role developed by [Mircea-Pavel ANTON](https://www.mirceanton.com).
