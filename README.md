### Install Boto
pip3 install boto
pip3 install boto3

### Clone Your Project Repository and Copy All The Project Code To `/var/lib/awx/projects`
sudo cp -rf ansible-tower-workflow-template-project/* /var/lib/awx/projects

### Check Playbook Syntax
ansible-playbook appserver_instance.yaml --syntax-check

## Execute Playbook
ansible-playbook appserver_instance.yaml -vvvv


## 1) Create And Setup Your Ansible Tower Environment


## 2) Access Your Ansible Tower Environment


## 3) Create Ansible Tower Project Resources
### A) Create Your Tower Project Inventory


