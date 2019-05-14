# Ansible Ubuntu Bionic (18.04) Server Provisioner
Ansible playbook to provision Ubuntu servers (web application, file server, database server and DNS server)

**Includes roles:**
- common: installs common applications (vim, git, ...)
- nginx_and_php
- postgres
- dnsmasq
- mssql_drivers (for using MS SQL from Ubuntu)
- deploy
- configurations
- redis

### Run:

    ansible-playbook [your_choice_of_server].yml -i hosts --ask-pass --ask-become-pass

    (You can omit --ask-pass if you are running the scipt locally only)
