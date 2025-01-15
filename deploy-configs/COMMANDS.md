# Kubectl and Minikube Commands 


## Manage Minikube Cluster
- `minikube start`

- `minikube start --vm-driver=hyperkit`

- `kubectl get nodes`

- `minikube status`

- `kubectl version`

- `minikube delete`

- `minikube status`

## Kubectl Commands
- `kubectl get nodes`

- `kubectl get pod`

- `kubectl get services`

- `kubectl create deployment nginx-depl --image=nginx`

- `kubectl get deployment`

- `kubectl get replicaset`

- `kubectl edit deployment nginx-depl`

## Debugging
- `kubectl logs {pod-name}`

- `kubectl describe pod {pod-name}`

- `kubectl get events`

- `kubectl exec -it {pod-name} -- bin/bash`

## Create Mongo Deployment
- `kubectl create deployment mongo-depl --image=mongo`

- `kubectl logs mongo-depl-{pod-name}`

- `kubectl describe pod mongo-depl-{pod-name}`

## Delete Deployment
- `kubectl delete deployment mongo-depl`

- `kubectl delete deployment nginx-depl`

## Create or Edit Config File
- `kubectl apply -f nginx-deployment.yaml`

- `kubectl get pod`

- `kubectl get deployment`

## Delete With Config
- `kubectl delete -f nginx-deployment.yaml`
