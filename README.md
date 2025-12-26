# Kubernetes
Learning and implementing


So to summarize, we have master and worker nodes on the master.

We have the etcd cluster which stores information about the cluster.
We have the kube scheduler that is responsible for scheduling applications or containers on nodes.
We have different controllers that take care of different functions like the node controller, replication controller, etc. 
We have the kube API server that is responsible for orchestrating all operations within the cluster.

On the worker node, we have the Kubelet that listens for instructions from the kube API server and manages containers and the kube proxy that helps in enabling communication between services within the cluster.
