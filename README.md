# kube-cluster-playbook
this Playbook ( kube-cluster.yml) is used to SetUp Kubernetes Cluster in EC2 Instance's

`Requirements`:
- Access Key : **********
- Secrete Key : ***********\
put both Key of your AWS account in the files name `(aws_key.yml)`, and Include this file name inside the Playbook

This Playbook first Create Secret Key for EC2 Instance to access the Instance, `So first Run this command on your localhost system`
- ssh-keygen -m PEM
- chmod 400 /root/.ssh/id_rsa.pub\
     after this, run playbook
     
This Playbook, Launch 3 Instance's, 1 for Master node and 2 Instance's for Worker node/
After Launching, start to SetUp Cluster over those Instance's
  
For do easily, `Use Ansible Collection`
###### Collection / Role :
**ansible-galaxy collection install ajeetrai266.kubecluster**\
this above command, Install collection in your Workspace\
It Collection, collect __3 different Role's__ for setup `Kubernetes Cluster`
