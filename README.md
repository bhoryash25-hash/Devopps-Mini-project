# SU-DevOps — DevOps Mini Projects

This repository contains coursework and DevOps mini projects submitted as part of the SU-DevOps collection.

## Repository Contents

| Path | Description |
|---|---|
| `Pratik_1037_Unit1_devops.docx` | Unit 1 DevOps submission |
| `Pratik_1037_Unit2_devops.docx` | Unit 2 DevOps submission |
| `Mini-Project-3/` | Student Academic Management Platform |
| `Mini-Project-3-Docker/` | Project 3 Dockerization branch snapshot |
| `Mini-Project-3-Jenkins/` | Project 3 Jenkins CI and Kubernetes branch snapshot |
| `Mini-Project-4/` | AWS infrastructure automation and application deployment |

## Mini Project 3 — Student Academic Management Platform

A Flask-based academic management API with student, course, enrollment, and marks functionality.

The original Project 3 repository contains development history for the application, Dockerization, and Jenkins/Kubernetes work.

## Mini Project 4 — AWS Infrastructure Automation

Demonstrates infrastructure provisioning and application deployment using:

- Terraform for AWS infrastructure
- Ansible roles and playbooks for server configuration and deployment
- Docker and Gunicorn for the Flask application
- Nginx as a reverse proxy
- AWS EC2, VPC, networking, security groups, and an encrypted S3 bucket

### Validation

The application was deployed to AWS and the following API operations were tested successfully:

- Health endpoint
- Student listing and creation
- Enrollment creation
- Marks submission
- GPA calculation

Evidence screenshots are available in `Mini-Project-4/screenshots/`.

### Cleanup

The Terraform-managed AWS resources for Mini Project 4 were destroyed after testing to avoid ongoing infrastructure charges. The deployment configuration and evidence remain in the repository.

## Notes

- Each project has its own folder and README where applicable.
- Do not commit credentials, private SSH keys, Terraform state files, or local environment folders.
