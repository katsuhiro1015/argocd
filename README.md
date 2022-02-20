# argocd

# metrics server

```
kubectl apply -f https://github.com/kubernetes-sigs/metrics-server/releases/latest/download/components.yaml
```

# prometheus

## CPU監視

```
rate(node_cpu_seconds_total{mode!="idle"}[1m])
```

## default namespaceのServiceMonitor

```

```