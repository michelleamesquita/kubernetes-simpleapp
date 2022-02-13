# kubernetes-simpleapp

Use k8s to deploy with minikube https://minikube.sigs.k8s.io/docs/start/

- kubectl create -f service-definition.yaml
- kubectl create -f simpleapp-pod.yml

- kubectl rollout status deployment/simpleapp-deployment

- minikube service simpleapp-service --url
