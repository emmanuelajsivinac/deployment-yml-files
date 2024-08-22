# Nginx app v1
This is a basic Nginx app. In this folder, you‘ll find the service YML file and the deployment YML file.

## Minikube - scripts
1. Make the deployment
`kubectl apply -f nginx-v1.yml`
2. Make the service
`kubectl apply -f ngnix-v1-service.yml`
3. Connect to Service
`minikube service nginx-v1-service`
or
`minikube service ngnix-v1-service —url`
