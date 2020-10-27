# Dev Local Environment

## Pre-requirements

- [Ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)

## How to install

### Without Git installed on machine

1. Download this repo https://github.com/pauloedwardo/local-environment/archive/main.zip
3. Execute the ansible command:

```bash
sudo ansible-playbook -e user={your-home-user} -v local.yaml
```

### With Git installed on machine

```bash
sudo ansible-pull -e user={your-home-user} -U https://github.com/pauloedwardo/local-environment.git
```

- TO DO
 - Add Terminator config
 - Add VS Code installation
 - Add Intellij
 - Add Postman
 - Add NPM
 - Add Node
 - Add Google Chrome
