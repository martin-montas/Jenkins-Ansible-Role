# Web Server Security Configuration

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
- [ ] Add support for Apache, nginx, PHP, etc. 
- [ ] Create proper users for the web server
- [ ] Add support for SSH, hardening.
- [ ] Add support for Mod Security
- [ ] Add support for Fail2Ban
- [ ] Add support for proper permissions on the web server file system
- [ ] Add support for Backup and Restore
- [ ] Ensure that directory browsing is disabled to prevent attackers 
      from seeing a list of files on your web server.
