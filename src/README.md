# DevOps Project: Docker Deployment using Jenkins and Ansible

## Project Overview
This project demonstrates a simple DevOps pipeline where a static web application is deployed using Docker. The automation is performed using Jenkins and Ansible.

## Technologies Used
- Docker
- Jenkins
- Ansible
- GitHub
- AWS EC2

## Project Structure

src/
│
├── pom.xml
├── Dockerfile
├── Jenkinsfile
├── ansible-playbook.yml
├── .gitignore
└── README.md

## Workflow

1. Source code is stored in GitHub.
2. Jenkins pipeline is triggered.
3. Jenkins executes the Ansible playbook.
4. Ansible installs Docker on the worker node.
5. Docker image is built using Dockerfile.
6. The Docker container runs the web application.

## Output

After successful deployment, the application will be accessible at:

http://<Worker_Public_IP>:8085

## Author
Premsagar
