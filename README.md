# Kubernetes RBAC Configuration

This repository contains Kubernetes RBAC (Role-Based Access Control) configuration files used to manage authentication, authorization, service accounts, and permissions within a Kubernetes cluster.

## Project Overview

The project demonstrates how to configure RBAC resources in Kubernetes using YAML manifests. It includes creation of Service Accounts, Roles, Role Bindings, and AWS authentication mappings for secure access management inside the cluster.

This setup helps enforce least-privilege access control and secure communication between users, applications, and Kubernetes resources.

---

## Files Included

| File Name | Description |
|---|---|
| `aws-auth.yaml` | Maps AWS IAM users/roles to Kubernetes RBAC permissions in EKS |
| `role.yaml` | Defines Kubernetes Role permissions |
| `sa-create.yaml` | Creates a Service Account |
| `sa.yaml` | Additional Service Account configuration |

---

## Technologies Used

- Kubernetes
- YAML
- RBAC
- AWS EKS
- IAM Authentication

---

## Key Concepts Covered

- Kubernetes RBAC
- Role and RoleBinding
- Service Accounts
- Authentication & Authorization
- AWS EKS User Mapping
- Least Privilege Access

---

## Prerequisites

Before deploying the configurations, ensure you have:

- Kubernetes Cluster
- kubectl installed
- AWS CLI configured (for EKS)
- Proper cluster access permissions

---

## Deployment Steps

### Clone Repository

```bash
git clone https://github.com/your-username/k8-rbac.git
cd k8-rbac
