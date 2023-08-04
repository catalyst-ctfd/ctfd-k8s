# ctfd-k8s

### Create k8s namespace
```kubectl create ns ctfd```

### Deploy MySQL
```kubectl apply -f ctfd-mysql-deployment.yaml```

### Deploy Redis
```kubectl apply -f ctfd-redis-deployment.yaml```

### Deploy ctfd
```kubectl apply -f ctfd-deployment.yaml```

### Expose ctfd service on OCP
```oc expose svc ctfd```
