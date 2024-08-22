# Nginx app v1
This is a basic Nginx app. In this folder, you‘ll find the service YML file and the deployment YML file.

## Minikube
1. Make the deployment <br>
`kubectl apply -f nginx-v1.yml`<br>
2. Make the service <br>
`kubectl apply -f ngnix-v1-service.yml`<br>
3. Connect to Service
`minikube service nginx-v1-service`<br>
or<br>
`minikube service ngnix-v1-service —url`<br>
