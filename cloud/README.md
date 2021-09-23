# Ansible Project
Starting Stopping the AWS EC2 Instance
# description
This playbook gives you good understanding on how you can make use of ansible for starting and stopping AWS EC2 instance.  
## Requirements
pip install ansible
pip install boto

## To start the instance

ansible-playbook aws_stop_start_instance.yaml -e ACTION=start

## To stop the instance

ansible-playbook aws_stop_start_instance.yaml -e ACTION=stop

note: you can run this playbook through CRONJOB to stop instance everyday at 10:00 pm to save resource consumption. 
