# FYP

### Name: Kuek Hui Li
### FYP ID: CCDS26-0152
### Project Title: Setting up of Infrastructure for SpeechLab Applications with Terraform and Terragrunt
### Supervisor: Prof Chng Eng Siong
### Start Date: 11 Aug 2026
### End Date: 12 May 2027

## Overview

As SpeechLab ASR application continues to go through modifications and updates, the infrastructure requirement changed. The current SpeechLab application is more complex as it consists of two different ways to process real time audio and recorded audio files. These new approaches introduce different storage, networking and availability requirements. Hence, the deployment of resources should be easy to create and modify without the need to manually configure every resource from scratch. Existing project infrastructure does not address the different requirements of development and production environment within a single reusable approach. The development environment requires lower costs and greater flexibility for testing and experimentation, while production environment should have stricter access control and better network security.
Another gap is the limited visibility of infrastructure changes before deployment. This project will check for configuration drift and generate a pre-deployment infrastructure cost estimation before user provision resources. Lastly, existing approach does not show how infrastructure will handle pods failure. This project will focus on using Terraform as an Infrastructure-as-Code (IaC) tool with Terragrunt to manage and organise infrastructure configurations across multiple environments.

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
