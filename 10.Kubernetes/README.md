  # 10.K8s Instalation
  
  ## Install Minikube, check cluster, enable dashboard, inrgess, change ram\cpu
  ```bash
  110  sudo apt install apt-transport-https
  112  wget https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
  113  chmod +x minikube-linux-amd64
  114  sudo mv minikube-linux-amd64 /usr/local/bin/minikube
  115  minikube version
  119  curl -LO https://storage.googleapis.com/kubernetes-release/release/`curl -s https://storage.googleapis.com/kubernetes-release/release/stable.txt`/bin/linux/amd64/kubectl
  120  chmod +x ./kubectl
  121  sudo mv ./kubectl /usr/local/bin/kubectl
  122  kubectl version -o json  --client
  123  minikube start
  124  kubectl cluster-info
  125  kubectl config view
  127  kubectl get nodes
  128  minikube ssh
  129  minikube stop
  130  minikube addons list
  131  minikube dashboard
  133  minikube start
  136  minikube addons enable ingress
  137  minikube addons list
  139  minikube status
  145  minikube stop
  146  minikube delete
  147  minikube start --memory 4096 --cpus
  ```
  
  ## Dashboard screenshot
  ![Dashboard!](https://github.com/AlexeyAsgard/myfirstrepo/10.Kubernates/Screenshot.png)
  
  ## K8s Ansible playbook reploy results
  ```bash

  ```
