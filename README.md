# GKE
Google Kubernetes Engine (GKE) PlayGround

## Prerequisites

1. Install Cloud SDK
2. Install kubectl
3. Login to GCP

```bash
# Install Google SDK
brew install google-cloud-sdk

# Install gke-gcloud-auth-plugin for use with kubectl
gcloud components install gke-gcloud-auth-plugin

# Install kubectl
brew install kubernetes-cli

# Login to GCP
gcloud init

# Add your account to the Application Default Credentials (ADC)
gcloud auth application-default login

# Enable Compute and Kubernetes Engine APIs
gcloud services list --enabled

gcloud services enable compute.googleapis.com
gcloud services enable container.googleapis.com

```