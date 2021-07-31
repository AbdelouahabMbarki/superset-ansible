# superset Ansible  Install 

## Prerequisites

Before you can run any of these playbooks, you will need to [install Ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html), and run the following command to download dependencies (from within the same directory as this README file):

    $ ansible-galaxy install -r requirements.yml

## Build and configure the servers (Local)

To configure VMs using Ansible, follow these steps :

Run `ansible-playbook configure.yml`

