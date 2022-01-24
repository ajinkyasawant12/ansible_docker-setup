# ansible_docker-setup
Ansible Playbook for Docker Setup 

# Docker on Ubuntu 18.04

This playbook will install Docker on Ubuntu setup
Customization can be doen using `vars/default.yml` file

## Running this Playbook

```command
ansible-playbook -i [inventory file] -u [remote user] playbook.yml
```