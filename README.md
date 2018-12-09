This repo contains ansible settings files, including a zabbix-agent role, playbook and inventory files to automate zabbix-agent deployment process. Supports Debian and RHEL systems. 

# Usage
1. Replace /etc/ansible files with files from this repo.
2. Add some new hosts to the inventory (see hosts file). Depending on what was added, you might want to update the existing or create a new playbook
3. Run the playbook

After zabbix-agent was successfully installed, you can now add new host(s) to Zabbix server. 

