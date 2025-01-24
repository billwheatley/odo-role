odo-role
=========

Ansible Role to install the odo tool (Red Hat OpenShift developer cli) on a given machine.  This will also install bash completion for `odo` as well.

This was also designed as part of a desktop provisioning playbooks found here <https://github.com/billwheatley/provision-desktop>

Requirements
------------

- Should work on most distros. Tested with Red Hat variants and Debian variants
- Optional - For bash completion a distribution with `dnf`, `dnf5`, `yum` or `apt`

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
