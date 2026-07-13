AWS EC2 STATIC WEBSITE DEPLOYMENT USING NGINX

Project Overview

This project demonstrates how to deploy a static HTML website on an AWS EC2 Ubuntu instance using the Nginx web server. The project includes EC2 instance creation, Linux server configuration, website deployment, and version control using Git and GitHub.

Technologies Used

- AWS EC2
- Ubuntu Linux
- Nginx
- Git
- GitHub
- SSH

 Project Objectives

- Launch an AWS EC2 Ubuntu instance.
- Configure Security Groups for SSH and HTTP access.
- Install and configure the Nginx web server.
- Deploy a static HTML website.
- Manage project files using Git and GitHub.

 Project Steps

1. AWS EC2 Setup
- Created an Ubuntu EC2 instance.
- Configured Security Groups to allow:
  - SSH (Port 22)
  - HTTP (Port 80)
- Connected to the instance using SSH.

 2. Linux Configuration
Executed the following commands:

```bash
sudo apt update
sudo apt upgrade -y
sudo apt install nginx -y
sudo systemctl status nginx
sudo systemctl restart nginx
df -h
free -h
ps aux
```
3. Website Deployment
- Created a custom `index.html` page.
- Replaced the default Nginx page.
- Verified website accessibility using the EC2 Public IP.

4. Git & GitHub
- Initialized a Git repository.
- Added project files.
- Committed the changes.
- Pushed the project to GitHub.

📁 Project Structure

aws-devops-assignment/
index.html
README.md

 How to Run

1. Launch an AWS EC2 Ubuntu instance.
2. Install Nginx.
3. Copy the `index.html` file to `/var/www/html/`.
4. Restart Nginx.
5. Open the EC2 Public IP in a web browser.

Output

The static website is successfully hosted on an AWS EC2 instance using the Nginx web server and is accessible through the EC2 Public IP.

 Key Learnings

- AWS EC2 instance provisioning
- Linux server administration
- Nginx web server configuration
- Website deployment on AWS
- Git and GitHub version control
- Secure SSH connectivity


#

AWS Cloud & DevOps Engineer (Fresher)

GitHub: https://github.com/DeepadharshiniKJ
