# Kubernetes_Project_1

To make the overall management of pods easier we use deployments.

Create deployment using:
> kubectl create -f <deployment_file_name>

To scale up the number of replicas in a deployment: 
> kubectl scale deployment <name_of_deployment> --replicas=n
