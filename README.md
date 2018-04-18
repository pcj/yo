YO - Devops Exercises
================

Welcome. This exercise is an opportunity to show us your ability to do operations. Here's the scenario. A summer intern committed this repository and left for school in the fall. We need this service as part of our business now. Your job is to get it into  production-worthy deployment setting in the cloud provider of your choice.

Do:
* Build the java code using `mvn package`. This will produce a jar file in `target` folder. 
* Deploy this in the cloud provider. 
* Provision Mysql database
* Provision a reverse-proxy in front of the java application. 
* Automate as much of the deployment to the cloud provider as you can using whatever tools you are most comfortable with.
* Write a smoke-test script to ensure that after deploy the application is running.

You shouldn't need to: 
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


