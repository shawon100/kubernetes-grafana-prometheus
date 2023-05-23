# kubernetes-grafana-prometheus
Latest grafana and prometheus Yaml with grafana dashboard for monitoring CPU, Memory, Netowrk, Storage etc. of your Kubernetes Cluster.

# Installation

```
kubectl apply -f prometheus-pv.yml
kubectl apply -f prometheus-pvc.yml
kubectl apply -f grafana-pv.yml
kubectl apply -f grafana-pvc.yml
kubectl create ns monitoring
kubectl apply -f grafana-prometheus.yaml
kubectl apply -f grafana-ingress.yml

```

