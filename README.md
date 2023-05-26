# Automation-Virtualhost-Apache2

This Ansible playbook automates the configuration of Apache2 and sets up virtual hosts for different domains. It installs Apache2, creates directories, copies HTML pages, configures virtual hosts, adds entries to the `/etc/hosts` file, and reloads Apache2.

## Prerequisites

- Ansible installed on the localhost.
- Sudo or root privileges on the localhost.

## command line to run it:
There's two command line that i give feel free to use one of them.

   ```bash
   sudo ansible-playbook automation.yml 
   ansible-playbook -i hosts automation.yml --ask-become-pass 

   ```
   # Remember put your ip adresse on line 60 in the script
