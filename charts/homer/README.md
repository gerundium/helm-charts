# helm-charts
Gerundium Public Helm charts

## Homer
This helm chart deploys the homer dashboard.

## TL;DR;

### Add helm repository
```bash
# Add
helm repo add gerundium https://gerundium.github.io/helm-charts/

# Update helm cache
helm repo update
```

### Install a chart
```bash
helm install <MY-RELEASE-NAME> gerundium/<CHART-NAME> [--values=overrides.yaml]
```