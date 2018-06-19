# splunk
Splunk clustering


############### Cloning path ########################

All files and folder sholud be on this path "/etc/ansible/roles"

$git clone https://github.com/jayagopalreddy/splunk.git /etc/ansible/roles/Splunkall

$mv /etc/ansible/roles/Splunkall/* /etc/ansible/roles/


########### Run below command ##############

$ansible-playbook /etc/ansible/roles/ec2_spin.yml && ansible-playbook -i /etc/ansible/roles/inventories /etc/ansible/roles/splunk_setup.yml
