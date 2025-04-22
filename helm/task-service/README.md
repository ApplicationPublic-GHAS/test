# Task Service Helm Chart

This Helm chart deploys a Task service (Java App) with a ConfigMap, Secret, Deployment, and Service.

## Prerequisites

- Helm 3.x
- Kubernetes cluster (version 1.18 or higher recommended)

## Installation

1. Clone the repository or download the chart.
2. Update `values.yaml` with your desired configurations (e.g., image repository, resource limits).
3. Install the chart:

```bash
helm install task-service ./task-service