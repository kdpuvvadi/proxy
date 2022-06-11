# Nginx Proxy Manager with Ansible Playbook

[![lint](https://github.com/kdpuvvadi/proxy/actions/workflows/lint.yml/badge.svg?event=push)](https://github.com/kdpuvvadi/proxy/actions/workflows/lint.yml)

Playbook works on both Debian & Red Hat family hosts. Using Ubuntu 20.04 pc as control node.

You need at least 2.9 or higher version of ansible.

## Setup

1. Install pip `sudo apt install python3-pip -y`
2. install ansible with pip `pip install ansible`
3. Install docker sdk for ansible `pip install docker`
4. Install requirements `ansible-galaxy collection install -r requirements.yml`

## Run

1. Clone the repo  `git clone https://github.com/kdpuvvadi/proxy.git proxy`.
2. copy `inventory.ini.j2` to `inventory.ini`.
3. Change host ip of the host.
4. copy `vars.yml.j2` to `vars.yml`.
5. Change the variable based on your preferences.

## Run the playbook

Run `ansible-playbook main.yml`

## Login Details

```ini
Email:    admin@example.com
Password: changeme
```

## more info & documentation of Nginx Proxy Manager

[Visit Nginx Proxy Manager Official Website](https://nginxproxymanager.com/)

## Portainer

To install portainer set `portainer_enable` value to `true`.
