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

### Deployments

```
kubectl create -f deployment-definition.yml
```

```
kubectl get deployments
```

```
kubectl get replicaset
```

```
kubectl describe deployment <YOUR_DEPLOYMENT_NAME_HERE>
```

```
kubectl get all
```

```
kubectl rollout status deployment/myapp-deployment
```

```
kubectl rollout history deployment/my-app-deployment
```

```
kubectl apply -f deployment-definition.yml
```

```
kubectl rollout undo deployment/myapp-deployment
```


### Services

```
kubectl create service-definition-yml
```

```
kubectl get services
```

```
kubectl describe service <YOUR_SERVICE_NAME_HERE>
```