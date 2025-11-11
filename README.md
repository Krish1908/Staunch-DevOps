# Staunch - Cloud & DevOps
This documentation explains my role and contributions as a Cloud & DevOps Engineer at Staunch, where I designed and implemented CI/CD pipelines for multiple internal projects using GitHub Actions and VM-based deployments.

## Overview
- Developed automated CI/CD pipelines for various in-house projects at Staunch.
Whenever the development team pushes new code to the GitHub repository, the respective pipeline is triggered, and the updated code is deployed automatically to the connected virtual machine (VM).

- All sensitive credentials and configuration files are securely managed using GitHub Secrets, ensuring a safe and compliant deployment process.
The pipeline status and logs are continuously monitored via the GitHub Actions dashboard to verify workflow success and identify issues in real time.

- Each pipeline includes security checks, validation steps, and service restarts to ensure consistent and reliable deployment across environments.
After every deployment, the project’s live status is verified through the respective hosted URL.

## Key Highlights
- Designed end-to-end CI/CD workflows using GitHub Actions.

- Implemented automated deployment to cloud VMs (AWS & Azure) via SSH.

- Configured environment variables, secret keys, and access tokens for secure runtime execution.

- Integrated validation and rollback mechanisms to prevent failed deployments.

- Achieved zero manual intervention during production pushes.

## Tech Stack

| Category | Tools & Services |
|-----------|------------------|
| Cloud Platforms | AWS, Azure |
| CI/CD Platform | GitHub Actions |
| Infrastructure | Terraform, Linux VM |
| Security | GitHub Secrets, SSH Keys |
| Monitoring | GitHub Actions Logs, URL Validation |
| Tools | Nginx, Systemd, Bash, YAML |

## Outcome

- Reduced deployment time from manual to fully automated pushes.

- Improved workflow reliability with built-in validation checks.

- Enhanced deployment visibility using GitHub Actions monitoring.

- Delivered a scalable, secure, and maintainable DevOps pipeline foundation for multiple active projects.
