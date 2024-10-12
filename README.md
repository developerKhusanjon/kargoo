# kargoo
Container deployment automation tool with pre-defined pipelines (... little hint, KotlinDSL will be used for this project)

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
![image](https://github.com/user-attachments/assets/8733595c-d800-480a-a602-0459d5709bcf)
![image](https://github.com/user-attachments/assets/e6553514-c2e6-4857-b841-94842a2a2938)
![image](https://github.com/user-attachments/assets/ce176b2e-f4d0-4558-a1ee-a2cbc47bb0fb)
![image](https://github.com/user-attachments/assets/5f684c7e-8fc0-4d30-a17c-da3b9df8ae85)





