### Create ReplicaSet

```
kubectl create -f replicasets/replicaset.yaml
```

### Get replicaSets

```
kubectl get replicaset
```

### Delete replicaSet

```
kubectl delete replicaset <YOUR_REPLICASET_NAME_HERE>
```

### Replace the replicaSet definition

```
kubectl replace -f replicasets/replicaset.yaml
```

### Get pods

```
kubectl get pods
```

### Deleting a specific pod

```
kubectl delete pod <YOUR_POD_NAME_HERE>
```

### Describe the replicaSet

```
kubectl describe replicaset <YOUR_REPLICASET_NAME_HERE>
```

### Scale replicaSet

```
kubectl scale -replicas=4 -f replicasets/replicaset.yaml
```

### Edit replica set on Editor

```
kubectl edit replicaset <YOUR_REPLICASET_NAME_HERE>
```
