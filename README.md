# Kubernetes

## Commands

Register ConfigMap

```bash
kubectl apply -f environments/dev/mongo-config.yml
```

Register Secret

```bash
kubectl apply -f environments/dev/mongo-secret.yml
```

Register Deployment and Service

```bash
kubectl apply -f environments/dev/mongo.yml
```

```bash
kubectl apply -f environments/dev/webapp.yml
```

List all

```bash
kubectl get all
```

List ConfigMap

```bash
kubectl get configmap
```

List Secret

```bash
kubectl get secret
```

List Pod

```bash
kubectl get pod
```

List Service

```bash
kubectl get svc
```

Describe Pod

```bash
kubectl describe pod webapp-deployment-5644797897-9249s 
```

Show logs of Pod

```bash
kubectl logs webapp-deployment-5644797897-9249s 
```

Describe Service

```bash
kubectl describe service webapp-service
```

Show Cluster IP

```bash
minikube ip
```

Go to the Cluster IP and add Port 30100 to the IP to reach the webapp
