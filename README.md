# deploying docker containers in K8s cluster
- bakend application docker containers are deployedn into Kubernetes cluster
- the cluster is made of 3 nodes, regarding Kubernetes containers orchestration, each microservice container is managed into a any available node

here is list of deployment files into k8s cluster:
- k8s-mysql-db
- ms-config-kube
- ms-registry-kube
- k8s-ms-address
- k8s-ms-company
- k8s-ms-employee
- k8s-ms-project

- the backend is located here: [backend](https://github.com/placidenduwayo1/K8s-AEPC-Back.git)
- deployment in docker images for the backend: [docker-compose](https://github.com/placidenduwayo1/K8s-AEPC-Docker-Deploy.git)