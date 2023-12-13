Description:
Installing Docker, configuring the EC2 instance, deploying and executing the Docker container containing the application are the steps involved in deploying an application on EC2 using Docker. 

Workflow:
1.	Create an EC2 instance with the Amazon Linux 2 AMI on AWS, using SSH to connect the EC2 instance.
2.	Use the SSH key pair associated with the instance to establish a secure connection.
3.	Install Docker on the EC2 instance by running the necessary commands.
4.	Update the package manager and install Docker using the appropriate package manager for Amazon Linux.
5.	Set up a Git repository to manage the project's code.
6.	Create a Dockerfile in the project's repository. The Dockerfile defines the instructions for building the Docker image and specify the base image, copy the application files into the image, 
7.	Create the secret key for all the sensitive information to keep safe.
8.	Created the workflow using GitHub Actions.
9.	Updated all the source files to the Git repository.
10.	Configure the workflow to run whenever changes are pushed to the main branch.
11.	Deploy all the process automatically to the EC2 instances.
12.	After successful deployment, we can host the website from EC2 instances using Public IP address.

Reflection:
It was necessary to carefully evaluate dependencies, environment variables, and the Dockerfile's overall structure before dockerizing the application. To make sure the Docker image was built correctly and had all the required parts.
