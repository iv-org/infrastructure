# Infrastructure

This repository contains the invidious infrastructure.

## Preparations

1. Install ansible
2. Install requirements: `ansible-galaxy install -r requirements.yml -p roles`

## Hosts
### invidious.io (old)

Install old requirements: `ansible-galaxy install -r requirements-old.yml -p roles`  

`ansible-playbook main.yml -i inventory.yml --ask-vault-pass`

### tin.invidious.io

`ansible-playbook tin.yml -i inventory.yml`
