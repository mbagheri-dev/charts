# Fleetman Helm Chart

This Helm chart deploys the Fleetman project on Kubernetes clusters.

## Prerequisites

- Kubernetes cluster
- Helm installed

## Installation

```bash
# Add Helm repository
git pull  https://github.com/mbagheri-dev/fleetman_project_charts.git

# Install the Fleetman Helm chart
helm install fleetman .
```

# Fleetman Helm Chart Configuration

The following table lists the configurable parameters of the Fleetman chart and their default values.

| Parameter      | Description                           | Default         |
| -------------- | ------------------------------------- | --------------- |
| `param_name`   | Description of the parameter          | `default_value` |
| `another_param`| Another parameter description         | `another_default` |
