# FYP_HuiLi
# FYP

### Name: Kuek Hui Li
### FYP ID: CCDS26-0152
### Project Title: Setting up of Infrastructure for SpeechLab Applications with Terraform and Terragrunt
### Supervisor: Prof Chng Eng Siong
### Start Date: 11 Aug 2026
### End Date: 12 May 2027

## Overview

The current SpeechLab ASR deployment required infrastructure and environment settings to be configured through separate manual commands. This can create inconsistencies between environments when recreating new resources, increase risk of configuration drift, and increase risk of human error when managing resources between development and production. This project will focus on buildinfg reusable infrastructure for SpeechLab applications on AWS using terraform and terragrunt.

Terraform is used to define and manage infrastructure as code. This is to allow the infrastructure to be defined in configuration files instead of creating them manually. This makes infrastructure more consistent, repeatable and easier to track and maintain. While, terragrunt is used to manage terraform configuration in development and production environement. Terragrunt allows both environments to resuse the same terraform modules while maintaining seperate configuration and state. The development environment is for developers to test, develop and make frequent changes to the SpeechLab infrastructure and applications. It can provide easier access and more flexiblity for development and testing. The production environment will have stricter security controls, more restricted access, and more controlled infrastructure changes to reduce risk of accidental changes or disruption.

## Video Updates

Playlist: https://www.youtube.com/playlist?list=PLLY7A8LxkLYI

## Roadmap / Milestones

- Phase 1: Understand the existing SpeechLab application architecture and infrastructure requirements.
- Phase 2: Set up the Terraform and Terragrunt project structure.
- Phase 3: Provision the AWS networking infrastructure, including the VPC, public and private subnets.
- Phase 4: Provision the Amazon EKS cluster, managed node group, IAM roles and Amazon ECR repository.
- Phase 5: Configure Amazon S3, Amazon EFS and monitoring with Prometheus and Grafana.
- Phase 6: Validate, document and optimize the infrastructure for reliability, security and cost.

## Contact

- Email: C230133@e.ntu.edu.sg

## References
