# devops.automation
Automation tool/framework used: ANSIBLE
pre-requisite: Anisble

setup:
inventory file needs to be defined with server or aws ec2 instance.

This Code has 3 segments:

1. Deployment
ansible-playbook -i inventory deployment.yml

2. Migration
ansible-playbook -i inventory migration.yml

3. Rollback
rollback will be triggered automatically if the build fails during Migration. 
