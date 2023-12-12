# Infrastructure

This repository contains the invidious infrastructure.

## Preparations

1. Install ansible
2. Install requirements: `ansible-galaxy install -r requirements.yml -p roles`

## Hosts

### dia.invidious.io

`ansible-playbook dia.yml -i inventory.yml`
