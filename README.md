# Ansible Role: Add user

An Ansible role to add a user.

## Requirements

This role requires Ansible 1.2 or higher.

## Role variables

Ansible variables are listed below with their default values.

```
user: "{{ ansible_ssh_user }}"
user_groups: []
public_key: "~/.ssh/id_rsa.pub"
```

## Example playbook

```
---
- hosts: webservers
  roles:
  	- opichon.add-user
```

## License

MIT

