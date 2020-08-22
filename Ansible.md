### What is Ansible?
- Its a simple automation language that is used in configuration management.
- Simple; Human readable automation, tasks are executed in order
- Ansible is an automation and orchestration tool popular for its simplicity of installation, ease of use in what concerns the connectivity to clients, its lack of agent for ansible clients and the multitude of skills.
- Ansible is an open-source, configuration management tool to provision IT environments, deploy software or be integrated to CI/CD pipelines.
- Ansible helps improve the scalability, consistency and reliability of your IT environment
- Ansible can automate repetitive system administration tasks
- Ansible uses SSH to push changes from a single source to multiple remote resources

### What can Ansible automate?
- **Provisioning**: Set up various servers (e.g Nginx web server) you need in your infrastructure
- **Configuration management**: Changes the configuration of an application, OS, or device; start and stop services; install or update applications; implement a security policy; or perform a wide variety of other configuration tasks.
- **Application deployment**: Make **DevOps** easier by automating the deployment of internally developed applications to your production systems.


### What does agentless mean?
- Refers to operations where no service, daemon or process needs to run in the background on the machine.
- Agentless doesn't require any agent to be installed for monitoring.
- You don't need to install software or firewall ports on the nodes that it manages.
- E.g you don't need to install Python, because it's already pre-installed in our Virtual Machine.
- No need to install dependencies

# ## Best practices of IaC:
1.**Managing infrastructure via source control**, providing a detailed audit trail for changes.
2.**Applying testing to infrastructure** in the form of unit testing, functional testing, and integration testing.
3.**Avoid written documentation**, since the code itself will document the state of the machine. This is particularly powerful because it means, for the first time, that infrastructure documentation is always up to date.
4.**Enables collaboration** around infrastructure configuration and provisioning, most notably between dev and ops.
