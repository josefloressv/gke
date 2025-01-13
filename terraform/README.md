# How to Run
1. Enable Compute and Kubernetes Engine APIs

```bash
# Enable
gcloud services enable compute.googleapis.com
gcloud services enable container.googleapis.com

# Validate services enabled
gcloud services list --enabled
```

2. Deploy with Terraform commands
```bash
terraform init
terraform plan
terraform apply
```
1. Connect to the GKE cluster
```bash
# List the GKE clusters

# Connect to the GKE cluster
gcloud container clusters get-credentials playground-s-11-82566600-gke --region us-central1
```