## minikube commands
### minkube status
### kubectl get node

## mongo-secret requires base64 encoded values, to generate it 
### echo -n mongouser | base64          result is => bW9uZ291c2Vy
### echo -n mongopass   | base64          result is => bW9uZ29wYXNz

## creating kubectl config for deployment
### kubectl apply -f mongo-config.yaml
### kubectl apply -f mongo-secret.yaml
### kubectl apply -f mongo.yaml
### kubectl apply -f webapp.yaml

## to get all kubectl pods
### kubectl get all
### kubectl get configmap
### kubectl get secret
### kubectl get pod
### kubectl describe service webapp-service
### kubectl describe pod podname
### kubectl logs podname

## to run app on browser
### kubectl get svc
### minikube ip
## kubectl get node -o wide
