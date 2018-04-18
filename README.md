YO - Devops Exercises
================

This exercise is an opportunity to show us your ability to do operations. 

Ok, so... A summer intern committed this repository and left for school in the fall. We need this service as part of our business now. Your job is to get it into  production-worthy deployment setting in the cloud provider of your choice.

Do:
* Sign up for a free trial of Amazon, Google Cloud, or Azure.
* Build the java code using `mvn package`. This will produce a jar file in `target` folder. 
* Deploy this in the cloud provider. 
* Provision Mysql database
* Provision a reverse-proxy in front of the java application. 
* Automate as much of the deployment to the cloud provider as you can using whatever tools you are most comfortable with.
* Write a smoke-test script to ensure that after deploy the application is running.

Don't: 
* Edit the Java code
* Pay for computing resources (sign up for a free account)
* Spend more than 4 hours on this. 

We recommend you use the free tier of one of the major cloud providers: Amazon, Google Cloud, or Azure. 

Here's how to return your work to us:
* Send us a pull request or zip up your working folder with your notes and scripts.
* Provide documentation as if we were doing an ops review on your code. Please include:
    * Description of the deployed system architecture
    * Screenshots of any cloud provider configuration (ie. firewall settings, vpcs, etc.)
    * Pointers to help us review your code
* Leave your environment running. Provide us with login information for the servers. Either send us a username/password, provide us with private key files, or add our keys (see attached `authorized_keys`)
