# Deploy to Kubernetes cluster using Jenkins CI/CD pipeline

Here will do continuous deployment to Kubernetes using Jenkins CD pipeline. I will be using kaniko tool from Google to build container image from within a container as we don't have access to docker engine and we use kubectl conatiner for deployment of the web application.

<img width="808" alt="image" src="https://user-images.githubusercontent.com/25737585/176170276-55c137fa-13f8-425c-9846-753173d5e876.png">

Please refer Kubernetes-Jenkins-CICD file for deatil steps

To Provision Kubernetes Minikube Cluster in Terraform, please refer the bellow repository 

https://github.com/swagat030/terraform-minikube-provision.git
