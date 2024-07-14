# Group Vars

Inventory group vars should be defined here.

File names should follow: `<group_name>.yml`

## Required vars for groups

### networking

- `ansible_user` - the user account for Ansible to use on the hosts
- `ansible_port` - the SSH port for Ansible to use to connect to the hosts
- `ansible_ssh_private_key_file` - path to the priv key Ansible should use to authenticate
