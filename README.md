# Deployment Instructions
This will spawn a full VPC with:
- internet gateway
- routing table
- security group (public, private and secure) 
- subnets (public and private)

On CLI you can run the command shown below. 
```
ansible-playbook  AWSVPC.yml -e "host_env=General" -f 100
```
You can modify a number of variables from the individual service variables

## Tower Setup
On Ansible Tower, you will need to let the scm sync and run the project on the UI
P.S.
You might need to define some define some variables to enable for proper deployment of assets and setup

