# kube-project
Creating a simple pipeline using Kubeflow.

Инструкция по установке Kubeflow на Minikube:
полная https://www.kubeflow.org/docs/distributions/minikf/minikf-vagrant/

краткая: 
1) установить Vagrant: https://www.vagrantup.com/downloads.html
2) и Virtualbox: https://www.virtualbox.org/wiki/Downloads
3) В терминале: vagrant init arrikto/minikf - создаем виртуальную машину с уже установленным minikube и kubeflow
4) Запускаем виртуальную машину: vagrant up
4) http://10.10.10.10 - появится терминал, в котором закончится установка. Будет выдана ссылка на Kubeflow dasboard
