# Automated Web Server Deployment

## Description

Developed a robust DevOps project using GitHub, Ansible, and Jenkins to automate the deployment of a web server on AWS EC2 instances. The system allows developers to commit code changes, triggering an automated pipeline that deploys the updated code onto designated EC2 instances. The web server dynamically displays content from HTML files provided by developers.

Technologies Used:
Version Control: GitHub
Automation Tool: Ansible
Continuous Integration/Continuous Deployment (CI/CD): Jenkins
Cloud Platform: Amazon Web Services (AWS)
Infrastructure: Managed 4 EC2 instances for hosting the web server
Responsibilities and Achievements:
Implemented a seamless automation process that reduces deployment time and enhances overall efficiency.
Configured Ansible playbooks for provisioning and configuring EC2 instances with necessary packages and dependencies.
Integrated Jenkins pipeline to trigger builds upon code commits, running tests and deploying the HTML content to the web server.
Skills Demonstrated:
DevOps Practices
Infrastructure as Code (IaC) with Ansible
Continuous Integration/Continuous Deployment (CI/CD)
AWS EC2 Instance Management
Version Control with Git and GitHub
Team Collaboration and Communication
Impact:
Streamlined the deployment process, resulting in faster time-to-market for new features and updates.
Enhanced team productivity by automating repetitive tasks, allowing developers to focus more on coding and less on deployment concerns..

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)

## Installation

[Prerequisites:
GitHub Account:
Ensure you have a GitHub account to create a repository for your project.

AWS Account:
Have an AWS account set up with necessary permissions to create and manage EC2 instances.

Ansible Installed:
Install Ansible on your local machine. You can follow the official documentation for installation steps based on your operating system.

Jenkins Installed:
Install Jenkins on a server or locally, depending on your setup requirements. Follow the official Jenkins installation guide for your platform.

Steps:
1. GitHub Repository Setup:
Create a new repository on GitHub for your project.

Clone the repository to your local machine using the git clone command.

2. Ansible Configuration:
Inside the repository, create a directory for Ansible playbooks and related files.

Write Ansible playbooks to provision and configure the AWS EC2 instances. These playbooks should include tasks for setting up necessary packages, dependencies, and configurations on the EC2 instances.

3. Jenkins Integration:
Set up a Jenkins pipeline/freestyle for your project.

Configure the Jenkins job to monitor the GitHub repository for changes. Use a webhook or Jenkins plugin to trigger builds on code commits.

Define the pipeline stages in the Jenkinsfile or pipeline script. Include stages for building, testing, and deploying the code to the EC2 instances.

4. AWS EC2 Instance Setup:
Ensure your AWS credentials are configured correctly on your local machine or Jenkins server.

Use Ansible to execute the playbooks, provisioning and configuring the EC2 instances as per your project requirements.

5. Web Server Deployment:
Write scripts or configuration files to handle the deployment of HTML content to the web server.

Ensure the web server configuration is part of your Ansible playbooks to automatically display the updated content.
## Usage

Here I have attached both images:
First one is of webserver and 
And the second is of command prompt of developer's machine in which he/she has written his/her HTML file.![Screenshot 2024-01-03 131910](https://github.com/furkanshaikh04/Project1/assets/140544257/93dd6771-3e40-4bd6-8edb-21d592d77713)
This is the image of the console output we get once our job gets build in jenkins ![Screenshot 2024-01-03 132342](https://github.com/furkanshaikh04/Project1/assets/140544257/437d8544-58ce-488d-b3ae-93ae89c79529)

In below link you can see how the final output looks like:

https://drive.google.com/file/d/19y16Xr-fviXzwIIm74ol_5iqp0BDg8Iz/view?usp=drive_link

