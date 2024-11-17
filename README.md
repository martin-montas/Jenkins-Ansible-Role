# Web Server Security Configuration



# How to start:

#### After changing the values at vars/ directory run the following command
```bash
ansible-playbook playbook.yml -i inventory.ini
```
and you will be done.

## For future development
- [ ] Add support for Apache, Nginx, PHP, etc. 
- [ ] Create proper users for the web server
- [ ] Add support for SSH, hardening.
- [ ] Add support for Mod Security
- [ ] Add support for Fail2Ban
- [ ] Add support for proper permissions on the web server file system
- [ ] Add support for Backup and Restore
- [ ] Ensure that directory browsing is disabled to prevent attackers 
      from seeing a list of files on your web server.
