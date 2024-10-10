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

![image](https://github.com/user-attachments/assets/9d4c9ff1-3539-41e3-8651-123a46293071)
![image](https://github.com/user-attachments/assets/94ba6793-2a58-44a2-a792-c42427f8c8c3)


