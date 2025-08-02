# EKS Echo App

This project deploys a simple echo app to Amazon EKS using:

- HashiCorp http-echo image
- Kubernetes Deployment, Service, and Ingress
- TLS & DNS via cert-manager and ExternalDNS

## Files
- `deployment.yaml` — deploys the echo app
- `service.yaml` — exposes it as ClusterIP or LoadBalancer
- `ingress.yaml` — configures Ingress with Route53 DNS
