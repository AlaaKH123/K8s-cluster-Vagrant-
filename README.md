# K8s-cluster-Vagrant-Ansible

Ce cluster kubernetes : a un master node et 2 workers 
pour executer le code de notre infrastucture on suivre le commandes suivantes : 

$cd K8s-cluster-Vagrant-Ansible // se placer dans le repo au se trouve le Vagrantfile et les playbooks
$vagrant up --provider virtualbox // si on veut changer le nombre de worker nodes il faut chnager la valeur du variable WORKERS_NUMBER dans le Vagrantfile 
$vagrant ssh master // pour acceder a la machine master puis faire la commmande kubectl get nodes :

![1](https://user-images.githubusercontent.com/124509691/235795928-18082e7a-c34e-4d53-baa2-646c6da5ce3a.PNG)

//pour acceder a un autre node on fait ca : vagrant ssh [NODE_NAME] 
