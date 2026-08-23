# The Redemption

AWS EKS infrastructure and Kubernetes deployment for The Redemption microservice.

## Components

* AWS VPC
* Amazon EKS
* Kubernetes Deployment
* Kubernetes Service
* HPA for autoscaling

## Deployment

### Terraform

```bash
terraform init
terraform plan
terraform apply
```

### Kubernetes

```bash
kubectl apply -f kubernetes/
```

## Repository Structure

```text
terraform/
kubernetes/
README.md
```

## Objective

Provide a highly available and scalable application that can handle sudden traffic spikes.
