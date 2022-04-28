## Namespace
```bash
kubectl create namespace redis-server
```

## Persistent storage PVC
```bash
kubectl apply -f pvc.yaml
```

## Redis deployment
```bash
kubectl apply -f deployment.yaml
```

## Service
```bash
kubectl apply -f service.yaml
```