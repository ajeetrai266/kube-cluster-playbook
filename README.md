# kube-cluster-playbook
this repository is used to SetUp Kubernetes Cluster in EC2 Instance's

- #### (amazon_ec2_launch ) : this Role is used to Launch EC2 Instance
For this, Required **Access Key** and **Secret Key** : put this Key file in Files directory of this role and __Include__ this Key file in Task folder

in this Role, 3 Instance's will be Launch
1 : for Master Node
2,3 : for Worker Node


- #### (Kube_master_node ) : this Role is used to setup 1 Master node in Ec2 Instance


- #### (Kube_worker_node ) : this Role is used to setup 2 Worker node in Ec2 Instance's

