# Bootstrap of Nativ Kubernetes Cluster on CentOS x Ansible

The following code include all required playbooks to bootsrap a Kubernetes cluster of 1 master and 2 workers.
(Send_output.tf is a bash script that extract required data from previous Terraform config to create an inventory.ini and a SSH Private Key)

To run the the initialization of the K8S cluster, make sure :
- your inventory.ini is correctly setup
- you got the right SSH Private Key associated with your machines (master and workers)
- run "ansible-playbook playbook.yml -i inventaire.ini"

