# Project 2 - The Server Commander

## Overview
This project demonstrates how to host a custom web page on an AWS EC2 instance using the Nginx web server.

## Technologies Used
- AWS EC2
- Amazon Linux 2023
- Nginx
- HTML
- Git
- GitHub

## Project Objective
Host a custom **"Welcome to DecodeLabs"** webpage on an AWS EC2 instance.

## Steps Performed
1. Launched an EC2 instance.
2. Connected to the instance using EC2 Instance Connect.
3. Updated the system packages.
4. Installed the Nginx web server.
5. Started and enabled the Nginx service.
6. Created a custom HTML page.
7. Hosted the webpage in the Nginx web root directory.
8. Accessed the webpage using the EC2 Public IP address.

## Commands Used

```bash
sudo dnf update -y
sudo dnf install nginx -y
sudo systemctl start nginx
sudo systemctl enable nginx
sudo systemctl status nginx
cd /usr/share/nginx/html
sudo nano index.html
sudo systemctl restart nginx
```

## Output
The custom webpage **"Welcome to DecodeLabs"** was successfully hosted on an AWS EC2 instance using Nginx.

## Screenshots
- EC2 Instance Running
- Nginx Installation
- Nginx Service Running
- Welcome to DecodeLabs Webpage

## Author
**Ankit Pandey**
