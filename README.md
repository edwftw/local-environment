# Dev Local Environment

## Pre-requirements
- Ubuntu (64 bits) - Installed and tested with 20.04.1 LTS
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

### What will be installed/donwloaded?
- Google Chrome
- Git
- Java (JDK) 8 and 11
- Visual Studio Code
- Python 3
- Terminator
- Postman
- Utilitaries: wget, htop, curl
- OBS Studio
- DBeaver CE
- Docker
- Jetbrains Toolbox 1.21.9712

### TO DO
 - Add Terminator config
 - Add NPM
 - Add Node