# aos_set_initial_pw
Sets up initial admin password on AOS-CX Switches

#### Example Playbook

```yaml
---
- name: Set initial admin password
  hosts: all
  gather_facts: false
  roles:
    - initial_admin_pw
```
