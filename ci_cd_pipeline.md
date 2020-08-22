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

## Continuous Delivery Benefits

- Automate the software Release Process
- Improve Developer Productivity
- Find and Address Bugs Quicker
- Deliver Updates faster


![cicdpipeline](imagesmd/ci_cd_pipeline.jpeg)

### Jenkins
Jenkins is an open-source automation tool written in Java with plugins built for Continuous Integration purposes. Jenkins is used to build and test your software projects continuously making it easier for developers to integrate changes to the project, and making it easier for users to obtain a fresh build. It also allows you to continuously deliver your software by integrating with a large number of testing and deployment technologies.

- Advantages of Jenkins include:
It is an open-source tool with great community support.
It is easy to install.
It has 1000+ plugins to ease your work. If a plugin does not exist, you can code it and share it with the community.
It is free of cost.
It is built with Java and hence, it is portable to all the major platforms


## How I have implemented CI/CD pipeline

- firstly created a continuous integration pipeline
- configured Jenkins to communicate with source code management of Github via a webhook
- configured the integration pipeline to listen for push to the dev branch
- further configuration - if ci pipeline test are successful merge the dev branch with the master branch.
- Used the functionality of having jenkins emailing us as the out come of the build as well as sending us a message on teams
- the Purpose of the CI pipeline is to test new code being added to the application through unit testing

## Second iteration of CI/CD pipeline

- In the second iteration of the task I implemented continuous delivery (cd) within our pipeline.
- to do so required reconfiguring our jenkins automation server so that upon a successful ci build our code would immediately be available in for use
