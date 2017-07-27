# Ansible Post Provisioning Playbooks  
  

## Purpose  
This repository will hold playbooks that can be run as post-provisioning tasks from within CloudForms. The playbooks can be stored in either Ansible Tower or by using Embedded Ansible within CloudForms. 

## Requirements  
 * CloudForms 4.5 in order to use Embedded Ansible
 * Ansible Tower if not using Embedded Ansible
 * Requirements vary for playbooks
  
## Playbooks  

### register_satellite6  
Register a newly provisioned VM with an existing Satellite 6 using the activation key provided  
Requires an activation key that has previously been created in Satellite 6. This activation key can be injected in a variety of ways but in this instance we will ask the users to enter the name in the CloudForms service dialog



