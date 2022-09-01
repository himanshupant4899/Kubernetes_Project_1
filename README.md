# Kubernetes_Project_1

This is an example voting app application deployed using kubernetes.

## General_template

```YAML
apiVersion:

kind:

metadata:

spec:
```

***

### Steps to follow:

1. Deploy PODS

2. Create Services (Cluster IP)
    1. redis
    2. db
    
3. Create Services (NodePort)
    1. voting-app
    2. result-app


***

Launching the pods and services:
> kubectl create -f <**pod or service file name**>

