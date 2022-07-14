# Ansible playbook to install homebrew packages on Mac machine

## Prerequsite

You need to install Ansible on your machine, aka the control node. Follow the official [Installation Guide](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#installing-ansible-on-specific-operating-systems).

Here an example on instaling Ansible on a macOS using homebrew:

```
❯ brew install ansible
```

## Running this playbook


```
❯ git clone https://github.com/kenno/mac-dev-playbook
❯ cd mac-dev-playbook
❯ ansible-playbook main.yml
```
