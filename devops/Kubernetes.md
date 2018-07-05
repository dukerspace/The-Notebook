### Kubernetest
[Learn online](https://www.katacoda.com/courses/kubernetes)

- Master Node : ทำหน้าที่ให้บริการ Kubernetes API (เป็น REST)
- Worker Node : ทำหน้าที่ run container
- Pod : กลุ่ม container
- Deployment : Replica Set + Pod
- Replica set : มีหน้าที่ทำให้ pod มีจำนวนเท่ากับที่กำหนดไว้



### kubectl
#### create
- kubectl create -f <file.yml>
- ex: kubectl create -f hello.yml

#### delete
- kubectl delete -f <file.yml>
- ex: kubectl delete -f hello.yml

#### get
- kubectl get pods
