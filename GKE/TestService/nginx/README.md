# Test Service
A simple nginx server to check functionality and make sure you're getting out on port 80.

## Deploy 

```
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
kubectl apply -f ingress.yaml

```