# Ubuntu Release Upgrade

This Ansible playbook automates and manages the process of upgrading Ubuntu systems to newer releases. It streamlines the upgrade workflow, handles common issues, and enables smooth transitions between Ubuntu versions.

## Features

- Step-by-step upgrade instructions
- Ansible automation for release upgrades
- Support for multi-hop upgrades without restarting the playbook between releases
- Troubleshooting tips and best practices

## Usage

Run the playbook as follows:

```bash
ansible-playbook -i my_inventory ubuntu-release-upgrade.yml
```