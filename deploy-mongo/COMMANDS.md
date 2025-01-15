## kubectl apply commands in order
    
- `kubectl apply -f mongo-secret.yaml`
- `kubectl apply -f mongo.yaml`
- `kubectl apply -f mongo-configmap.yaml` 
- `kubectl apply -f mongo-express.yaml`

## kubectl get commands

- `kubectl get pod`
- `kubectl get pod --watch`
- `kubectl get pod -o wide`
- `kubectl get service`
- `kubectl get secret`
- `kubectl get all`

## kubectl debugging commands

- `kubectl describe pod mongodb-deployment-xxxxxx`
- `kubectl describe service mongodb-service`
- `kubectl logs mongo-express-xxxxxx`

## give a URL to external service in minikube

- `minikube service mongo-express-service`

## enable the ingress controller

- `minikube addons enable ingress`
- `kubectl apply -f ingress-service.yaml`
- `kubectl get ingress`
- `kubectl describe ingress`
- `minikube tunnel`
-  change the hosts file in windows system32/drivers/etc/hosts
-  change the hosts file in linux /etc/hosts
