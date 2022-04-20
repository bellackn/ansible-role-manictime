# ansible-role-manictime

Sets up a local ManicTime server (Docker) and installs the client package on macOS.

⚠️ Work in progress

## Example playbook

```yaml
---
- name: Set up ManicTime
  hosts: localhost
  roles:
    - bellackn.manictime
```

Run it with `--ask-become-pass` since you will need your password to install the client package.
