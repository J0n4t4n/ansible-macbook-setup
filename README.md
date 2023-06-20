# Ansible Macbook Setup

An Ansible playbook used to configure my work Macbook with all essential software and configuration.

Install dependencies:

```bash
ansible-galaxy install -r requirements.yml
```

Run via:

```bash
ansible-playbook main.yml -K
```

Linting is done via:

```bash
yamllint .
ansible-lint main.yml
```
