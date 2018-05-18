# go-dev-environment
Ansible playbooks to install/configure Golang dev env

Use:
1. Edit hosts and enter IPs/hosts
2. ansible-playbook -i hosts < playbook > -e whom=< remote user >

Example:
ansible-playbook -i hosts go.yml -e whom=root
