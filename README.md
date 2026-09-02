# FYP

### Name: Kuek Hui Li
### FYP ID: CCDS26-0152
### Project Title: Drift-Aware Multi-Environment Infrastructure Provisioning for SpeechLab ASR Using Terraform and Terragrunt
### Supervisor: Prof Chng Eng Siong
### Start Date: 11 Aug 2026
### End Date: 12 May 2027

## Overview

This project focuses on improving the cloud infrastructure supporting the SpeechLab ASR application, which processes both recorded audio files in batch and real-time audio streams. As the application continues to evolve, its infrastructure requirements have become more complex, introducing different compute, storage, networking, security, and availability requirements.

This FYP covers the design and deployment of reusable AWS infrastructure using Terraform and Terragrunt, with separate configurations for development and production environments. It also focuses on improving infrastructure management and reliability through configuration drift detection and restoration, pre-deployment cost estimation, and infrastructure monitoring. In addition, the project will improve application resilience by configuring the Kubernetes infrastructure to respond to pod failures, replace failed pods, and restore the desired application state.

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
