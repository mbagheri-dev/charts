# Fleetman Helm Chart

This Helm chart deploys the Fleetman project on Kubernetes clusters.

## Prerequisites

- Kubernetes cluster
- Helm installed

## Installation

```bash
# Add Helm repository
helm repo add fleetman-repo https://github.com/mbagheri-dev/fleetman_project_charts.git

# Install the Fleetman Helm chart
helm install fleetman fleetman-repo/fleetman_project_charts
