# Ansible Playbooks

Small Ansible playbooks used to manage my Ubuntu server.

## Included

* `update_server.yml` — update installed packages
* `reboot_server.yml` — reboot server
* `inventory` — target hosts

## Goal

Practice automating the common infrastructure tasks and reduce manual administration.

## Usage

```bash
# Run package updates
ansible-playbook -i inventory update_server.yml

# Reboot server
ansible-playbook -i inventory reboot_server.yml
```