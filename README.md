# Nextcloud Helm Charts

[Helm](https://helm.sh) repo for different charts which can be installed on [Kubernetes](https://kubernetes.io)

### Add Helm repository

To install the repo just run:

```bash
helm repo add ornias https://ornias.github.io/helm/
helm repo update
```

### Helm Charts

* [nextcloud](https://ornias.github.io/helm/)

  ```bash
  helm install nextcloud ornias/nextcloud
  ```
