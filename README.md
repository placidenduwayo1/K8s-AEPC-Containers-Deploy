# K8s containers orchestration
- backend application docker containers are deployedn into K8s cluster
- the cluster is made of 3 nodes, regarding K8s containers orchestration, each service container is managed into any available node

here is list of deployment files into k8s cluster:
- k8s-mysql-db/
    - k8s-mysql-deploy-svc.yml
    - mysql-pv-pvc.yml
    - mysql-secret.yml
- k8s-config-service.yml
- k8s-gateway-service.yml
- k8s-ms-address.yml
- k8s-ms-company.yml
- k8s-ms-employee.yml
- k8s-ms-project.yml

the backend is located here: [git](https://github.com/placidenduwayo1/K8s-AEPC-Back.git) and 
deployment in docker images for the backend: [git](https://github.com/placidenduwayo1/K8s-AEPC-Docker-Deploy.git)