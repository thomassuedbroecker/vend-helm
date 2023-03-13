# vend-helm

Just deploy the [vend application](https://github.com/thomassuedbroecker/vend) with a Helm chart.

### Verify the helm chart

```sh
cd ./charts
helm dependency update ./vend-helm/
helm install --dry-run --debug vend-helm-chart ./vend-helm/
```

### Install helm chart

```sh
cd /charts
helm lint ./vend-helm
helm install vend-helm ./vend-helm
```

### Uninstall helm chart

```sh
cd ./charts
helm uninstall vend-helm
```

