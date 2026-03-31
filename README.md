# AWS Cloud Project V2

This project started as a rebuilt AWS S3 static website and was later expanded into a broader cloud project using EC2, NGINX, GitHub, IAM, Bash, and Docker.

## What this project includes

- Hosted a static website using AWS S3
- Rebuilt the project from scratch for reinforcement
- Launched an EC2 instance and hosted a live website
- Installed and configured NGINX on Linux
- Used Git and GitHub for version control
- Created a Bash deployment script
- Attached an IAM role to EC2 for secure AWS access
- Ran the website inside a Docker container

## Key concepts learned

- S3 buckets and static website hosting
- EC2 as a virtual server
- Linux file navigation and editing
- NGINX as a web server
- Git add, commit, and push workflow
- Bash scripting for deployment automation
- IAM roles vs access keys
- Docker images, containers, ports, and volumes
- Security groups and inbound HTTP/SSH rules

## Project workflow

1. Built and updated files locally in VS Code
2. Pushed code to GitHub
3. Pulled code onto EC2
4. Deployed the site with Bash and Docker
5. Verified the live site through the EC2 public IP

## Live site

EC2 Public IP:
`http://18.144.15.202`

## Files in this repo

- `index.html` - website content
- `deploy.sh` - deployment script
- `README.md` - project documentation

## Why this project matters

This project demonstrates a progression from simple static hosting to a more realistic cloud workflow using compute, networking, permissions, version control, automation, and containers.
