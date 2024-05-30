# moonbeam helm charts

The Helm chart repository for moonbeam.


Set it up with:
```bash
helm repo add moonbeam https://moonbeam-nyc.github.io/helm-charts/
helm repo update
```

Now you can install the snorlax Helm chart:
```bash
helm install snorlax moonbeam/snorlax \
    --namespace snorlax \
    --create-namespace
```
