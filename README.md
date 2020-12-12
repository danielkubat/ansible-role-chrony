# ansible-role-chrony

![Ansible Lint](https://github.com/danielkubat/ansible-role-chrony/workflows/Ansible%20Lint/badge.svg)
![YAML Lint](https://github.com/danielkubat/ansible-role-chrony/workflows/YAML%20Lint/badge.svg)

Resources required to install Chrony on RHEL/CentOS/Fedora.

## Installation

To start the process locally, install the role:

```
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

```
ansible-playbook playbook.yml
```

_Currently supported only on RHEL/CentOS/Fedora._

[ansible]: https://docs.ansible.com/ansible/latest/index.html
