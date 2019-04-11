# my-shift
openshift origin cluster on a mac book

Tools used to build the cluster include:
virtualbox
vagrant
git 
ansible
python 
go 


Based on works from:
https://github.com/minishift/minishift
https://github.com/kubernetes/minikube
https://github.com/scorputty/vagrant-ha-openshift


Basic Architechtur:
Vagrant:
* builds and mantains the VirtualBoxs
* Network is build and man

You can configure the Cluster to contain how many Masters, Workers Nodes should be spun up. 
Centos7 is used as the base
You can configure which OKD version to run in the cluster. 

Ansible manages the configuration of the VM and the installation of OKD. 

Python/GO is used as a wrapper/Orcistation tool to manage the whole system. 



