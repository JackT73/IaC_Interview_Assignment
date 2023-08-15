# IaC_Interview_Assignment

### Requirements
Using IaC:
- [x] Set up a managed node VM
- [ ] On that VM, set up some kind of http resource (something that responds to GETs)
- [ ] Set up a reverse proxy in front of it
- [ ] Demonstrate performing a GET against the reverse proxy
- [ ] Trace the http request from your client, through the proxy, to the http server

#### Progress
- Created Control Node VM through Azure Portal.
- SSH'd into the VM and installed Python, Pip, and Ansible
- Installed Azure CLI and created an Azure Service Principal for Ansible
- Wrote a playbook to create Managed Node VMs

##### Resources Used
- [Configure Ansible on an Azure VM](https://learn.microsoft.com/en-us/azure/developer/ansible/install-on-linux-vm?tabs=azure-cli#install-ansible-on-an-azure-linux-virtual-machine)
- [Create an Azure service principal for Ansible](https://learn.microsoft.com/en-us/azure/developer/ansible/create-ansible-service-principal?tabs=azure-cli)
- [Create a Linux virtual machines in Azure using Ansible](https://learn.microsoft.com/en-us/azure/developer/ansible/vm-configure?tabs=ansible)
- [Ansible's Azure Documentation](https://docs.ansible.com/ansible/latest/collections/azure/azcollection/azure_rm_virtualmachine_module.html)
