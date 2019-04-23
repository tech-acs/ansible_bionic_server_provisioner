# Ansible Ubuntu Bionic (18.04) Server Provisioner
Ansible playbook to provision an Ubuntu web server (nginx+laravel)

**Includes roles:**
- common: installs common applications (vim, git, ...)
- nginx_and_php
- postgres     
- deploy
- configurations
- redis

### Run:

    ansible-playbook provision.yml -i hosts --ask-pass --ask-become-pass
