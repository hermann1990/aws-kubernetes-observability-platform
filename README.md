# aws-kubernetes-observability-platform
Production-style Kubernetes observability and DevOps platform on AWS EC2
Overview

This project demonstrates a production-style DevOps and observability platform deployed on AWS using Kubernetes on EC2. It reflects real-world DevOps practices used in consulting and enterprise environments, including container orchestration, CI/CD automation, and system observability.

The platform is designed to improve deployment reliability, system visibility, and incident response time.

Architecture

AWS EC2 (Kubernetes cluster)

Dockerized microservices

Kubernetes (manual cluster on EC2)

OpenTelemetry for metrics, logs, and traces

AWS CloudWatch for infrastructure monitoring

What I Implemented

Provisioned AWS EC2 infrastructure for Kubernetes workloads

Deployed containerized services using Docker and Kubernetes

Integrated OpenTelemetry to collect metrics, logs, and distributed traces

Designed CI/CD pipelines for automated build and deployment

Implemented monitoring to improve system visibility and troubleshooting

Technologies Used

AWS EC2, IAM, Security Groups

Docker

Kubernetes

OpenTelemetry

CI/CD (Jenkins / GitHub Actions)

Linux

Use Case

This setup mirrors how DevOps teams deploy and monitor microservices in real production environments, focusing on scalability, reliability, and observability.
