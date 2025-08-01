# Project 3: Runtime Secrets Management with Azure Key Vault

## Overview

This project simulates a common enterprise challenge: secure secret management for containerized applications. Leveraging Azure Key Vault and AKS pod identities, secrets are dynamically injected at runtime without exposing them in images or code.

## Business Problem Solved

Hardcoded or embedded secrets lead to breaches and compliance issues. Enterprises require centralized, auditable secret storage with secure runtime retrieval.

## What You Will Build

- Azure Key Vault for centralized secret storage.
- AKS cluster integrated with Azure AD Workload Identity.
- Sample microservice fetching secrets at runtime via pod identity.
- Kubernetes RBAC policies limiting secret access.

## Enterprise Impact

- Enhances security posture by eliminating secret exposure.
- Supports compliance with regulatory requirements.
- Streamlines secrets rotation and auditing.

## Step-by-Step

1. Create Azure Key Vault and store application secrets.
2. Enable Azure AD workload identity on AKS cluster.
3. Deploy microservice configured to authenticate and retrieve secrets securely.
4. Apply least-privilege Kubernetes RBAC policies.
5. Validate secrets access and audit logs.

## Prerequisites

- Azure subscription with AKS
- Kubernetes CLI (kubectl) and Azure CLI

## References

- [Azure Key Vault](https://learn.microsoft.com/en-us/azure/key-vault/secrets/overview)
- [Azure AD Workload Identity for AKS](https://azure.github.io/aad-pod-identity/)
