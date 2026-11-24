\# Experiment 10 - Minikube and Nagios



\## MINIKUBE



minikube start



kubectl create deployment mynginx --image=nginx



kubectl get deployments



kubectl get pods



kubectl describe pods



kubectl expose deployment mynginx --type=NodePort --port=80 --target-port=80



kubectl scale deployment mynginx --replicas=4



kubectl get services



kubectl port-forward svc/mynginx 8081:80



minikube dashboard



kubectl delete deployment mynginx



kubectl delete service mynginx



minikube stop



\## NAGIOS



docker pull jasonrivers/nagios:latest



docker run --name nagiosdemo -p 8888:80 jasonrivers/nagios:latest



Open http://localhost:8888



Username: nagiosadmin

Password: nagios



docker ps



docker stop nagiosdemo



docker rm nagiosdemo



docker rmi jasonrivers/nagios:latest

