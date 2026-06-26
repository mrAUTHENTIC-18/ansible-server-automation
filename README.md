# ansible-server-automation
# Ansible Server Automation

## Project Overview

This project automates the provisioning and configuration of Amazon Linux 2023 EC2 instances using Ansible.

## Features

- Install Git
- Install Docker
- Install Nginx
- Create a devops user
- Create an /app directory
- Deploy a custom HTML portfolio page
- Manage multiple servers from a single control node

## Technologies

- AWS EC2
- Amazon Linux 2023
- Ansible
- Nginx
- Docker
- Git & GitHub

## Project Structure

```
ansible_lab/
├── inventory
├── site.yml
├── web.yml
├── install-nginx.yml
└── README.md
```

## Run

```bash
ansible-playbook -i inventory site.yml
```

## Author

**Palmer**

DevOps Engineer
