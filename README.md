# deploying docker containers in K8s cluster
- bakend application docker containers are deployedn into Kubernetes cluster
- the cluster is made of 3 nodes, regarding Kubernetes containers orchestration, each microservice container is managed into a any available node

here is list of deployment files into k8s cluster:
- k8s-mysql-db/
    - k8s-mysql-deploy-svc.yml
    - mysql-pv-pvc.yml
    - mysql-secret.yml
- k8s-config-service.yml
- k8s-regisgateway-service.yml
- k8s-ms-address.yml
- k8s-ms-company.yml
- k8s-ms-employee.yml
- k8s-ms-project.yml

the backend is located here: [backend](https://github.com/placidenduwayo1/K8s-AEPC-Back.git) and 
deployment in docker images for the backend: [docker-compose](https://github.com/placidenduwayo1/K8s-AEPC-Docker-Deploy.git)