![Ansible](Images/ansible.png)

# Asnbile

:sparkles::fireworks::tada: Important points about this Repository!!!!! :tada::fireworks::sparkles:


- This Repository will act as a complete Guide for Ansible, explaining each concept of Ansible with their practical code scripts written in YAML Language!
- For brief introduction of Ansible please refer to the section given below!

# What is Ansible?

- It is an Automation Tool & also the best automation tool available in the market.

- 

- In Technical terms Kubernetes is also known as the container cluster orchestration tool, which means that it is used to manage the complete cluster of container with various resources and services.

# Instructions to Install Kubernetes and launch a single node cluster!
* First of all, to clarify the meaning of single node cluster, it is referred to a scenario in which a node act as a master node & simultaneously it acts as a worker node also.

* To install Kubernetes, download the software named as "minikube".
  * Link for the complete guide for the installation of the software: https://kubernetes.io/docs/tasks/tools/install-minikube/

  * There is a requirement for this software to work & that is there should be VirtualBox present in the host system of the Kuberenetes or base system on which Kubernetes has to be installed.
  * In detail explanation of the pre-requisites & all other things for the installation is listed in the link given above.

* After installing the minikube software, run the command **"minikube start"** to start the single node Kubernetes cluster.

* To check the IP of the cluster master node, run the command **"minikube ip"**. By default the Ip of the Kubernetes cluster is **192.168.99.100** !

* Now using "kubectl" command, Kubernetes cluster is accessible, information regarding the same is also been listed in the link provided above for installation of Kubernetes.

* To stop the Kubernetes cluster run the command **"minikube stop"**.

**Note: Minikube by default uses <i>Docker</i> as the container, although Kubernetes has the support for many other containerization tools!**


# Some of the general command for breaking the ice with the Kubernetes cluster!

* Command to check all the PODS running in the cluster: **"kubectl get pods"**.

* Command to delete all the PODS running in the cluster: **"kubectl delete pods --all"**.

* Command to check all the running PODS in the cluster: **"kubectl get pods"**.

* Command to check all the running Replication Controller in the cluster: **"kubectl get rc"**.

* Command to check all the running Replica Set in the cluster: **"kubectl get rs"**.

* Command to check all the running PVC win the cluster: **"kubectl get pvc"**.

* Command to check all the running PV in the cluster: **"kubectl get pv"**.

* Command to delete most of the running services in the cluster: **"kubectl delete all --all"**.


# License of this Repository!
To check out the License for this Repository please click [here!](https://github.com/HarshitDawar55/Kubernetes/blob/master/LICENSE)
