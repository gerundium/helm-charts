# helm-charts
Gerundium Public Helm charts

## Welcome friend!

This repository contains helm charts for my [homelab](https://gerundium.github.io/).

## TL;DR;

### Add helm repository
```bash
# Add
helm repo add gerundium https://gerundium.github.io/helm-charts

# Update helm cache
helm repo update
```

### Install a chart
```bash
helm install <MY-RELEASE-NAME> gerundium/<CHART-NAME> [--values=overrides.yaml]
```

## My notes

### Create helm chart

```bash
helm package charts/homer
helm repo index .
```