## Deploy Nginx Proxy Manager with Ansible Playbook

[![lint](https://github.com/kdpuvvadi/Nginx-Proxy-Manager-Ansible/actions/workflows/lint.yml/badge.svg)](https://github.com/kdpuvvadi/Nginx-Proxy-Manager-Ansible/actions?query=workflow%3Alint)


You need atleast 2.9 or higher version of ansible. 
### Setup

1. Install pip `sudo apt install python3-pip -y`
2. install ansible with pip `pip install ansible` 
3. Install docker sdk for ansible `pip install docker`
4. Install requirements `ansible-galaxy collection install -r requirements.yml`

### Run

1. Clone the repo  `git clone https://github.com/kdpuvvadi/Nginx-Proxy-Manager-Ansible.git proxy`. 
2. copy `example.inventory.ini` to `inventory.ini`.
3. Change host ip of the host.
4. copy `example.vars.yml` to `vars.yml`.
5. Change the variable based on your preferences.

### Run the playbook

Run `ansible-playbook main.yml` 

### Login Details

```
Email:    admin@example.com
Password: changeme
```
## more info & documentation of Nginx Proxy Manager

[Visit Nginx Proxymanager Official Website](https://nginxproxymanager.com/)

### Install portainer

To install portainer set `portainer_enable` value to `true`.
