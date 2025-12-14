# Install Jenkins with Docker 

## why install jenkins with docker 
because the jenkins server when run it local Kubernetes cluster like minikube dosen't run the docker commands like build...


## insatlling steps
befor you run the \
kubectl apply -f command \
you need to build the Docker file first:\
eval $(minikube docker-env) #If you use minikube cluster\
docker build -t jenkins-with-docker:lts .\
then you nedd to apply the kubectl by numbers from 01 first to 04


### Thank you

