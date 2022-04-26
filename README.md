## Prerequisites

Ansible 2.8

Root user must have ssh access with key authorization

## Run playbook

Setup cluster:

```sh
ansible-playbook --key-file=~/.ssh/id_rsa setup.yaml
```