# Installation
```
$ kubectl create namespace spark
$ helm repo add bitnami https://charts.bitnami.com/bitnami
$ helm repo update
$ helm install spark bitnami/spark -n spark -f values.yaml
```

by : hermawanln
