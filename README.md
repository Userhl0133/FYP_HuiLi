# FYP

### Name: Kuek Hui Li
### FYP ID: CCDS26-0152
### Project Title: Drift-Aware Multi-Environment Infrastructure Provisioning for SpeechLab ASR Using Terraform and Terragrunt
### Supervisor: Prof Chng Eng Siong
### Start Date: 11 Aug 2026
### End Date: 12 May 2027

## Overview

This project focuses on improving the cloud infrastructure supporting the SpeechLab ASR application, which processes both recorded audio files in batch and real-time audio streams. As the application continues to evolve, its infrastructure requirements have become more complex, introducing different compute, storage, networking, security, and availability requirements.

This FYP focuses on designing and managing reusable AWS infrastructure using Terraform and Terragrunt, with separate configurations for development and production environments. Beyond infrastructure provisioning, the project will improve the management and visibility of Terraform-managed infrastructure through configuration drift detection and restoration, pre-deployment cost estimation, and monitoring of provisioned infrastructure health and resource utilisation. The infrastructure will be validated using the existing SpeechLab batch and real-time processing workflows to ensure that the provisioned resources can support the application's requirements.

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
