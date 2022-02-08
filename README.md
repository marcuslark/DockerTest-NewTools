# Multicontainer application

It contains React client, Node.js backend, PostgreSQL and Nginx

You can run it in development mode: docker-compose up --build
It contains Dockerfiles for client and server, push it to your DockerHub repository to be able to use Kubernetes

# Upgraded Project to be able to use Kubernetes

# -- To make the nginx controller run in the cluster 
- kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v1.1.1/deploy/static/provider/cloud/deploy.yaml --force=true


# -- To make the Server and the Client run in the cluster 
- kubectl apply -f k8s (k8s is the folder name)



# -- Good to know commands
- kubectl get pods

- kubectl get services

- kubectl get pv

- kubectl get 
