### Infrastructure as Code IaC
- IaC is used to speed up the process of configuration management or orchestration
#### Ansible
- Infrastructure automation tool for configuration management
- Connects via ssh

#### Advantages of Ansible
Ansible doesn’t use agents, and its code is written in YAML in the form of Ansible Playbooks, so configurations are very easy to understand and deploy.

- simple
- Agentless
- IT automation
- Uses connection with ssh

#### Practical example
- create 3 instances
- One Ansible controller instance - that will dictate the configuration of the two other instances in our network
The controller virtual machine is the vm that has Ansible installed on it and the other instances do not require Ansible to be downloaded on them (Agentless)


Ubuntu 16.04 vm - webApp

Ubuntu 16.04 vm - db


### How does Ansible fit with devops
- what are the advantages of using ansible in DevOps
- Time efficient
- open-source
- Automates the the configuration of servers and virtual machines
- 
