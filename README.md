# kargoo
Container deployment automation tool with pre-defined pipelines

CRUD commands:
  create deployment     -    kubectl create deployment [name] 
  edit deployment       -    kubectl edit deployement [name]
  delete deployment     -    kubectl delete deployment [name]

Status of components:
  nodes
  pods
  services
  relicaset
  deployment

Debugging pods:
  log to console              -     kubectl logs [pod_name]
  get interactive terminal    -     kubectl exec it [pod_name] -- bin/bash
  get info about pod          -     kubectl describe pod [pod_name]

Use configuration file for CRUD:
  apply a configuration file   -     kubectl apply -f [file_name]
  deleter with config file     -     kubectl delete -f [file_name]
  
