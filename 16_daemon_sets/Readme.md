*Daemon sets ensure that every single node in the kubernetes cluster runs the
same pod resource

* It is useful if you want to ensure that a certain pod is running on every
single kubernets node

*When a node is added to the cluster,a new pod will be started

*When a node is removed,the pod will not be rescheduled on another node.
