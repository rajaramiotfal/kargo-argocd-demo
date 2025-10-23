# Kargo + Argo CD Multi-Environment Demo

This repository demonstrates a Kargo + Argo CD GitOps pipeline for three environments: Dev, QA, and Prod.
- Kargo detects new Docker image tags and updates Git manifests automatically.
- Argo CD syncs those changes to the respective cluster.
