# Web Server Security Configuration

## Introduction:
This Ansible role is build for security and setup of web servers automation.

## Prerequisites:
- Ansible 2.1 or higher
- Python 3.7 or higher
- Git


## Dependencies:
- [community.general.ufw](https://galaxy.ansible.com/ansible/general-ufw)
- [community.general.apt](https://galaxy.ansible.com/ansible/general-apt)
- [community.general.user](https://galaxy.ansible.com/ansible/general-user)
- [community.general.group](https://galaxy.ansible.com/ansible/general-group)


## How get started:

### 1. How to install:
```bash
git clone https://github.com/martin-montas/Web-Server-Sec-Ansible.git
```

### 2. After changing the values at vars/ directory run the following command
```bash
ansible-playbook playbook.yml -i inventory.ini
```

### For future development:
- [ ] Add support for Apache, Nginx, PHP, etc.
- [x] Create proper users for the web server
- [x] Add support for SSH, hardening.
- [ ] Add support for Mod Security
- [x] Install Fail2Ban
- [x] Configure Fail2Ban 
- [ ] Add support for proper permissions on the web server file system
- [ ] Add support for Backup and Restore
- [ ] Ensure that directory browsing is disabled to prevent attackers
      from seeing a list of files on your web server.
