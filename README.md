# MyLink-Infra
This repository contains the infrastructure configurations such as kubernetes deployments etc for **MyLink** app.

#### Key points about *MyLink-Infra*
* It uses a self-hosted **Kubernetes** cluster.
* All other components such as **MariaDB**, **Elasticseach**, **MinIO** etc. are also self-hosted and configured.
* Only **API Gateway** has **Ingress** configured and other services are not accessible from outside.
* Each service has **Secrets**, **ConfigMap**, **Deployment** and **Service** blocks configured in Kubernetes. 
