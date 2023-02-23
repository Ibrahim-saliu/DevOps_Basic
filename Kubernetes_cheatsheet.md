****** KUBERNETES BOOTCAMP ******
=========================================
USING THE kubernets.io/doc/tutorials/
=========================================

- To Create a Cluster
minikube version


- To start a cluster
minkube start


To get cluster info
kubectl cluster-info


- To get cluster nodes
kubectl get nodes 


- To create a deployment
kubectl create deployment <deployment_name> --image=<image_url:tag> 


- To list your created deployments
kubectl get deployments



- To list your pods
kubectl get pods -o wide


- To get extesive information about your pods
kubectl describe pods


- To view Logs
kubectl logs <pod_name>


- To execute a command in a container running in a pod
kubectl exec <pod_name> --<your_cmd>
e.g kubectl exec <POD_NAME> -- env   == will list env variables
    kubectl exec -ti <POD_NAME> -- bash == will launch bash terminal in the container


