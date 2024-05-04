# Learning Kubernetes
Commands I learned in this course are as follows:
minikube start -> start a cluster.
kubectl cluster-info
kubectl get nodes
kubectl get namespaces
kubectl get pods -A
kubectl get services -A
kubectl apply -f <file.yaml>
kubectl delete -f <file.yaml>
kubectl get deployments -n <namespace_name>
kubectl get pods -n <namespace_name>
kubectl delete pod <pod_name>
kubectl describe pod <pod_name> -n <namespace_name>
#busybox kubectl apply -f busybox.yaml
kubectl get pods -n <namespace_name> -o wide
kubectl exec -it <pod_name> --bin/sh
kubectl logs <pod_name> -n <namespace_name>
minikube tunnel
kubectl get services -n <namespace_name>
kubectl api-resources
kubectl get pods -n kube-system
kubectl logs etcd-minikube -n kube-system
