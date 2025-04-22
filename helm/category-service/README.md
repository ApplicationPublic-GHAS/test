# Node Service Helm Chart

This Helm chart deploys a Node.js service with a ConfigMap, Secret, Deployment, and Service.

## Prerequisites

- Helm 3.x
- Kubernetes cluster (version 1.18 or higher recommended)

## Installation

1. Clone the repository or download the chart.
2. Update `values.yaml` with your desired configurations (e.g., image repository, resource limits).
3. Install the chart:

```bash
helm install node-service ./node-service