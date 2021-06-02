# ansible-role-chrony

![Ansible Lint](https://github.com/danielkubat/ansible-role-chrony/actions/workflows/ansible-lint.yml/badge.svg)
![YAML Lint](https://github.com/danielkubat/ansible-role-chrony/actions/workflows/yamllint.yml/badge.svg)

Resources required to install Chrony on RHEL/CentOS/Fedora.

## Installation

To start the process locally, install the role:

```bash
ansible-galaxy install danielkubat.chrony
```

create a playbook and save as `playbook.yml`:

```
---
- hosts: localhost
  become: yes
  roles:
  - role: danielkubat.chrony
```

and then execute it:

```bash
ansible-playbook playbook.yml
```

_Currently supported only on RHEL/CentOS/Fedora._
