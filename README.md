# kubernetes-practice-and-architecture
Kubernetes architecture Notes  
This repository contains my learning notes and hands-on understanding of Kubernetes architecture and core components
## Control plane Components 
API server:   Entry Point for Cluster Communication 
Schedular: Assign Pods to Worker Nodes 
Controller Manager : Maintain Desire cluster state 
Etcd : Cluster configuration datastore
## worker Node Components 
Kubelet: Manage pod lifecycle on nodes 
Kube-proxy: Handles networking rules 
Container run time : Runs containers 
