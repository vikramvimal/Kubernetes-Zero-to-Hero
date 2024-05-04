Basic Commands:

kubectl get: List resources.
kubectl describe: Show detailed information about a resource.
kubectl create: Create a resource from a file or from stdin.
kubectl apply: Apply a configuration to a resource.
kubectl delete: Delete resources by filenames, stdin, resources, and names, or by resources and label selector.
kubectl edit: Edit a resource on the server.

Viewing and Finding Resources:

kubectl get pods: List all pods in the default namespace.
kubectl get nodes: List all nodes in the cluster.
kubectl get services: List all services in the namespace.
kubectl get deployments: List all deployments in the namespace.
kubectl get namespaces: List all namespaces in the cluster.
kubectl describe pod <pod-name>: Describe details of a pod.
kubectl logs <pod-name>: Print the logs from a container in a pod.
kubectl get events: Show events from all namespaces.
kubectl top node: Show metrics for a given node.
kubectl top pod <pod-name>: Show metrics for a given pod.

Managing Resources:

kubectl create deployment <name> --image=<image>: Create a deployment.
kubectl expose deployment <name> --port=<port>: Expose a deployment as a service.
kubectl scale deployment <name> --replicas=<count>: Scale a deployment.
kubectl rollout status deployment <name>: Check the status of a rollout.
kubectl rollout history deployment <name>: View rollout history.
kubectl rollout undo deployment <name>: Rollback to a previous deployment.

Interacting with Nodes:

kubectl get nodes: List all nodes in the cluster.
kubectl describe node <node-name>: Describe a node.
kubectl drain <node-name>: Drain a node in preparation for maintenance.
kubectl cordon <node-name>: Mark a node as unschedulable.
kubectl uncordon <node-name>: Mark a node as schedulable.

Working with Namespaces:

kubectl create namespace <name>: Create a new namespace.
kubectl get pods --namespace=<namespace>: List all pods in a specific namespace.
kubectl describe namespace <name>: Describe details of a namespace.
kubectl delete namespace <name>: Delete a namespace and all resources within it.
