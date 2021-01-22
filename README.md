odo-role
=========

Ansible Role to install the odo tool (Red Hat OpenShift developer cli) on a given machine.  This will also install bash completion for `oc` as well.

This was also designed as part of a desktop provisioning playbooks found here <https://github.com/billwheatley/provision-desktop>

Requirements
------------

- A distribution with `dnf` or `yum` or `apt`

Role Variables
--------------

none

Example Playbook
----------------

```yaml
- name: My Playbook
  hosts: desktop
  roles:
    - role: odo-role
```

License
-------

GPLv2

Author Information
------------------

Contact via [Github](https://github.com/billwheatley/)
