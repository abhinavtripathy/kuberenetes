# kuberenetes
Everything Kuberenetes

## Basic Commands for using minikube 

```
kubectl cluster-info // cluster information

kubectl get nodes // get all nodes

kubectl create deployment $name --image=$imageURL // create a deployment with an image

kubectl get deployments // list of all deployments

kubectl describe pods // in depth information on pods

kubectl get services // list of all services 

kubectl expose deployment/$deployment_name --type="NodePort" --port $port // make deployment publically accessible

// scaling 

kubectl scale deployments/$deployment_name --replicas=$number_of_replicas

kubectl get pods -o wide
```
