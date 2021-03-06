# Software-Production-Engineering-2021-Jenkins-Resources

A repository containing material covered in lab session on Jenkins for the SPE course at IIIT-B. 

## How to use this repository ?

You can find the slides covered in class [here](https://docs.google.com/presentation/d/1hTTM1Xei3CwP-2G8qwAlgdDIAVhDY3YuLQsAH3-_oM8/edit?usp=sharing). Follow along with the slides. The slides have links to specific parts of this repository like installing jenkins, setting up jenkins etc which should help you to get started with jenkins. 

## System Requirements install Jenkins
 - Atleast 4 GB RAM
 - Make sure nothing else is running on port 8080 (default port of Jenkins) or open jenkins in a different port.
 - If you doing a native installation, make sure Java8 is installed. 
 - If you use MacOS make sure [homebrew](https://brew.sh/) is installed.
 - If you are installing on docker, make sure you have docker up and running.
 
 ## Installing Jenkins
 
There are plenty of resources online that tell you how to install jenkins but here are are a few guides that I have tried and tested. I also recommend you to read the articles rather than copy pasting the commands blindly.
 
 ### Ubuntu
 
Install Java8 and then follow [Digital Ocean's guide to installing jenkins on Ubuntu 18.04](https://www.digitalocean.com/community/tutorials/how-to-install-jenkins-on-ubuntu-18-04) starting directly from Step 1.
 
 ### MacOS

Install Java8 then follow Option1 in [How to install and configure jenkins on mac os](https://coralogix.com/log-analytics-blog/how-to-install-and-configure-jenkins-on-the-mac-os/)
 
 ### Docker
 
Install docker and then follow Option2 in [How to install and configure jenkins on mac os](https://coralogix.com/log-analytics-blog/how-to-install-and-configure-jenkins-on-the-mac-os/)

## Post-installation setup.

This step is same for all regardless of your operating system. Follow this [link by digital ocean](https://www.digitalocean.com/community/tutorials/how-to-install-jenkins-on-ubuntu-18-04#step-4-%E2%80%94-setting-up-jenkins)

## Tutorial on Git Plugin

Refer to the [slides](https://docs.google.com/presentation/d/1hTTM1Xei3CwP-2G8qwAlgdDIAVhDY3YuLQsAH3-_oM8/edit?usp=sharing).
Public repository mentioned in the slides is this https://github.com/aSquare14/simple-script

## Suggested exercises to do after the lab session [Not Graded]

Setup a Hello World Program following [this](https://www.jenkins.io/doc/pipeline/tour/hello-world/)
Follow [Build a Java app with maven tutorial](https://www.jenkins.io/doc/tutorials/build-a-java-app-with-maven/) by jenkins.io . In this they have used docker to setup jenkins, you can skip that part and follow the rest of the steps to learn about setting up a complete CI/CD pipeline. 

## Any questions

If you have any questions regarding the lab session, feel free to open an issue in this repository.

## Resources

- [Why we should use Continouos Integration and Deployment ?](https://css-tricks.com/continuous-integration-continuous-deployment/)
- [What is CI/CD? by RedHat ](https://www.redhat.com/en/topics/devops/what-is-ci-cd)
- [Jenkins Official Documentation](https://www.jenkins.io/doc/book/)
- [Top 20 Continuous Integration Tools](https://www.guru99.com/top-20-continuous-integration-tools.html)
 
