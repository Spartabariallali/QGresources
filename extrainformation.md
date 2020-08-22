### Make notes on

### MVC - Model view controller

### API
API stands for Application Programming Interface. In short this is software that acts as an intermediary between two applications with the main purpose of allowing communication between the two applications. In other words, an API is the messenger that delivers your request to the provider that your requesting from it and then delivers the response back to you.

#### Webscrapping
Webscrapping is the process of using a program or algorithm to extract and process large amounts of data from the web.

#### Type of Requests
Requests or HTTP requests characterise what action you are going to take by referring to the API.
- GET: For simple retrieval of information about your account, Droplets, or environment, you should use the GET method. The information you request will be returned to you as a JSON object.

The attributes defined by the JSON object can be used to form additional requests. Any request using the GET method is read-only and will not affect any of the objects you are querying.

- POST: To create a new object, your request should specify the POST method.

The POST request includes all of the attributes necessary to create a new object. When you wish to create a new object, send a POST request to the target endpoint.

- PUT: To update the information about a resource in your account, the PUT method is available.

Like the DELETE Method, the PUT method is idempotent. It sets the state of the target using the provided values, regardless of their current values. Requests using the PUT method do not need to check the current attributes of the object.


### TDD

### Python OOP

### Vagrant

Vagrant
vagrant is a tool used by devops engineers to help build and configure virtual enivronments.

vagrant features can be broken down into a few key areas:
vangrantfile
boxes
networking
provisioning
plugins

#### Vagrantfile

a vagrantfile is a configuration file that uses Ruby programming language syntax.
It is easy to understand ans can be quickly tested by making a change and then running the vagrant up to see whether the expected results have been implemented
vagrantfiles can easily be shared and added into version control.
its lightweight and contains everything needed for another user to replicate a virtual environment/application

#### Provisioning

Provisioning in Vagrant is a way to configure the vagrant machine.
Through provisioning you are able to install software dependencies as the machine is being created.

#### Advantages of Vagrant

Vagrant allows you the user to easily package up a virtual environment that can be shared with other developers.
These virtual environments can be configured to match the production environment of the application/code is running
This can help minimise the presence of bugs/errors when the code is deployed to the production environment
a big advantage of vagrant is the vagrant configuration file known as vagrantfile can be easily created, edited and tested.
The syntax of a vagrantfile is easy to understand and offers a simple way to build complex virtual environments

#### Vagrant and developers

Vagrant gives access to developers to package up their code/application into an easily sharable fully-fledged development environment.
This can then be used by other developers who do not have the original production environment and are using different OS such as Linux, Windows or macOS.

#### Vagrant and operations

The operations team can easily and quickly test deployment tools and scripts using vagrant.
Vagrant supports many popular deployment tools such as: Docker, Puppet and Chef.

---

### Continuous Integration

Continuous Integration is a development practice in which the developers are required to commit changes to the source code in a shared repository several times a day or more frequently. Every commit made in the repository is then built. This allows the teams to detect the problems early. Apart from this, depending on the Continuous Integration tool, there are several other functions like deploying the build application on the test server, providing the concerned teams with the build and test results, etc.

## 1.
First, a developer commits the code to the source code repository. Meanwhile, the Jenkins server checks the repository at regular intervals for changes.
## 2.
 Soon after a commit occurs, the Jenkins server detects the changes that have occurred in the source code repository. Jenkins will pull those changes and will start preparing a new build.
## 3.
 If the build fails, then the concerned team will be notified.
## 4.
If built is successful, then Jenkins deploys the built in the test server.
## 5.
 After testing, Jenkins generates a feedback and then notifies the developers about the build and test results.
## 6
It will continue to check the  source code repository for changes made in the source code and the whole process keeps on repeating.

### Continuous Delivery

Continuous delivery is the software practice of preparing changes to code to automatically be transferred for release to production. Continuous delivery expands upon continuous integration by deploying all code changes to a testing environment and/or a production environment after the build stage. When properly implemented, developers will always have a deployment-ready build artifact that has passed through a standardized test process. 


### Jenkins
Jenkins is an open-source automation tool written in Java with plugins built for Continuous Integration purposes. Jenkins is used to build and test your software projects continuously making it easier for developers to integrate changes to the project, and making it easier for users to obtain a fresh build. It also allows you to continuously deliver your software by integrating with a large number of testing and deployment technologies.

- Advantages of Jenkins include:
It is an open-source tool with great community support.
It is easy to install.
It has 1000+ plugins to ease your work. If a plugin does not exist, you can code it and share it with the community.
It is free of cost.
It is built with Java and hence, it is portable to all the major platforms


- AWS
- VPC


### Infrastructure as Code IaC
configuration management
created a virtual machine using virtualbox and vagrant on our on premise machine
moved our nodejs webapp onto our virtual machine through synchronisation


### Single point of failure

creating replica sets - which are copies/images of essential resources within your network. In one instance goes down - there is a load balancer in place that balances the load amgongst the remaining resources.

### autoscaling and replica sets
