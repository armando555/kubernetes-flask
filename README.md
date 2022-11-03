# Execute
Verify the cluster
```bash
kubectl get pod
```

Later, create the config flask and the secret

```bash
kubectl apply -f flask-config.yaml
```
now, create the deployment and service 
```bash
kubectl apply -f flask.yaml
```

Finally, create the deployment and service of webapp
```bash
kubectl apply -f webapp.yaml
```