# vmware

Currently running and hosting these playbooks from an CentOS 7.5 VM - running on my Work Laptop. 

Update /etc/ansible/hosts with the vCenter ip address

Example commands for running a playbook:

ansible-playbook vm_switch.yml -vvv -e "host=<ip address>"


ansible-playbook vm_switch.yml -vvv -e "user=username password=password host=<ip address> vmtemplate=template vm_memory=memory cpu=cpu disk=<disk_size>"
