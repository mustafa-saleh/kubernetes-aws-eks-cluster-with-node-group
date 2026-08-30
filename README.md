# Kubernetes on AWS - EKS Cluster with Node Group

Kubernetes (often abbreviated as K8s) is an open-source container orchestration platform designed to automate the deployment, scaling, management, and networking of containerized applications across a cluster of hosts.

## Overview

Kubernetes emerged as a platform for microservices applications. microservices communicate either through API calls, message broker (redis, rabbitmq) or service mesh (istio).

Amazon Elastic Kubernetes Service (Amazon EKS) is a fully managed service that lets you run upstream, certified Kubernetes on AWS without maintaining your own control plane

**Amazon EKS Key Features**

- **Managed Control Plane**: AWS handles the availability, scaling, and security patches of the Kubernetes master nodes across multiple Availability Zones.
- **Compute Options**: You can run your worker nodes using Amazon EC2 instances or serverless containers with AWS Fargate.
- **Native Integration**: Deeply integrates with core AWS tools like Virtual Private Cloud (VPC) for networking, Identity and Access Management (IAM) for security, and Elastic Load Balancing for traffic.
- **Standard Tooling**: Supports standard open-source tools like kubectl and Helm to manage deployments.

## Demo Project

Create AWS EKS cluster with a Node Group

## Technologies used

Kubernetes, Linux, AWS (EKS, VPC, ELB, EC2, ASG, CloudFormation)

## Project Description

- Configure necessary IAM Roles
- Create VPC with Cloudformation Template for Worker Nodes
- Create EKS cluster (Control Plane Nodes)
- Create Node Group for Worker Nodes and attach to EKS cluster
- Configure Auto-Scaling of worker nodes
- Deploy a sample application to EKS cluster

## Implementation Guide

