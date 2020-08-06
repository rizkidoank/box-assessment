# Implementation

## Toolings
> NOTE: These toolings are opinionated, implementation details not provided

### Client
- `terraform` for infrastructure as code, managing the infrastructure
- `kubectl` for interaction with kubernetes server
- `helm` for package manager, templating, and deployment for services

### Server (Operational)
- `jenkins` could be one of the CI/CD options
- `nginx` could be one of the ingress
- `AWS ALB` used as load balancer
- `prometheus-operator` for observability
- `AWS Parameter Store` for secret management
- `Kubernetes RBAC` combined with `AWS IAM` for client access control
- `Kubernetes ConfigMap` for config management
- `Kubernetes Namespace` for environment separation
- `Kubernetes PersistentVolume` for stateful storage
- `Kubernetes Snapshot` for backup restore mechanism