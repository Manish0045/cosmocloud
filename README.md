# Cosmocloud Deploy - Helm Chart

This Helm chart is designed to deploy a simple application stack consisting of:

- **Backend** (shreybatra/sample-backend)
- **Frontend** (shreybatra/sample-frontend)
- **Redis** (redis)

## How to Deploy

1. Clone this repository.
2. Install Helm on your machine (if not already installed).
3. Use the following Helm command to install the chart:

   ```bash
   helm install testapp cosmocloud-deploy --atomic --timeout 30s
