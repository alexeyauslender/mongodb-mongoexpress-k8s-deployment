# mongodb-mongoexpress-k8s-deployment

# How to run
1. Install nginx ingress service following documentation: https://kubernetes.github.io/ingress-nginx/deploy/#quick-start
2. Run following to apply resources to your local cluster
```  
kubectl apply -f mongodb-deployment.yaml
kubectl apply -f mongo-secret.yaml
kubectl apply -f mongoexpress-deployment.yaml
kubectl apply -f mongoexpress-configmap.yaml
``` 