# vend-helm

Just deploy the vend application with a Helm chart.

### Verify the helm chart

```sh
cd /charts
helm dependency update ./vend-helm/
helm install --dry-run --debug vend_helm_chart ./vend-helm/
```

### Install helm chart

```sh
cd /charts
helm install vend_helm_chart ./vend-helm
```

### Uninstall helm chart

```sh
cd /charts
helm uninstall vend_helm_chart
```

