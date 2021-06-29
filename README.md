## Deploy Nginx Proxy Manager with Ansible Playbook

You need atleast 2.9 or heighr version of ansible. 
### Install Ansible

`pip install ansible` 

### Install Docker SDK for Ansible

`pip install docker`

### Install Docker community edition with ansible galaxy

`ansible-galaxy collection install -r requirements.yml`

### Download the Playbooks

Clone the repo with `git clone https://github.com/kdpuvvadi/Nginx-Proxymanager-Ansible.git nginx-proxy`. Edit the vars file desired values and change the host ip & host ssh username.

### Run the playbook

 * `ansible-playbook main.yml` ( installs docker, append `-K` for sudo password prompt if necessary).
 
 

### Login Details
```
Email:    admin@example.com
Password: changeme
```
## more info & documentation of Nginx Proxy Manager

[Visit Nginx Proxymanager Official Website](https://nginxproxymanager.com/)

### Install portainer

To install portainer set `portainer_enable` value to `true`.