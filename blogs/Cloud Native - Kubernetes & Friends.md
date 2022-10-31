# Cloud Native - Kubernetes & Friends

## Kubernetes

### kubectl

#### get services
```
kubectl get services --all-namespace
```

#### get pods
```
kubectl get pods --all-namespaces
```

#### view logs
```
kubectl logs -n zadig zadig-post-upgrade-5s4rp
```

#### hich Node Pod Runs On ?
```
kubectl get pod -o wide
```

#### [Kubernetes - Assigning Pod to Nodes](https://tachingchen.com/blog/kubernetes-assigning-pod-to-nodes/)
