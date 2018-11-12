# vmware

Currently running and hosting these playbooks from a CentOS VM running on my Work Laptop. 

Example commands for running a playbook:

ansible-playbook vm_switch.yml -vvv -e "host=<ip address>"


ansible-playbook vm_switch.yml -vvv -e "user=username password=password host=<ip address> vmtemplate=template vm_memory=memory cpu=cpu disk=<disk_size>"
