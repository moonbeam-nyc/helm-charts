# moon-society helm charts

The Helm chart repository for moon-society.


Set it up with:
```bash
helm repo add moon-society https://moon-society.github.io/helm-charts/
helm repo update
```

Now you can install the snorlax Helm chart:
```bash
helm install snorlax moon-society/snorlax \
    --namespace snorlax \
    --create-namespace
```
