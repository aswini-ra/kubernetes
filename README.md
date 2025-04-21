# kubernetes Commands:

To create cluster:
eksctl create cluster --config-file=ekys.yaml

To list available nodes
kubectl get nodes

To create namespace
kubectl apply -f 01-namespace.yaml

To get namespaces list: # default we have 3 admin namespace
kubectl get namespaces




