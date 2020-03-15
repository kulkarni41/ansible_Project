# ansible_Project:
Requirement: 
- Use Ansible to install NGINX on a debian based linux distribution such as Ubuntu. 
- Configure it to listen on port 3200. 
- Configure a virtual host as www.example.com to route traffic to a backend host named localhoston port 3400.
- Other Virtual Host to route traffic to custom 404 page. 
- Nginx should start on VM reboot

Assumptions:
1. ssh setup is already in place for all the hosts in ansible inventory file. 
2. inventory file with debina group containing all the servers where nginx need to be installed.

command to execute : 
ansible-playbook nginx_install.yaml	
