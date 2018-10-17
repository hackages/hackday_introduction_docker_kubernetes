# Kubernetes
## Kubernetes exercice part 1.

### Install minikube 

#### macOS

As minikube will need to create a VM, you'll need to download Hyperkit or xHyve 
and then you'll be able to install minikube itself.

Hyperkit driver:
https://github.com/kubernetes/minikube/blob/master/docs/drivers.md#hyperkit-driver

xhyve driver : 
https://github.com/kubernetes/minikube/blob/master/docs/drivers.md#xhyve-driver

Minikube : 
https://github.com/kubernetes/minikube#macos
kubectl : 
https://kubernetes.io/docs/tasks/tools/install-kubectl/#kubectl-install-curl-0

#### Linux

As minikube will need to create a VM, you'll need to download KVM 
and then you'll be able to install minikube itself.

KVM : 
https://github.com/kubernetes/minikube/blob/master/docs/drivers.md#kvm-driver

Minikube : 
https://github.com/kubernetes/minikube#linux
kubectl : 
https://kubernetes.io/docs/tasks/tools/install-kubectl/#kubectl-install-curl-1

#### Windows

As minikube will need to create a VM, you'll need to download hyperV
and then you'll be able to install minikube itself.

hyperV:
https://github.com/kubernetes/minikube/blob/master/docs/drivers.md#hyperV-driver

Minikube :
https://github.com/kubernetes/minikube#windows
kubectl :
https://kubernetes.io/docs/tasks/tools/install-kubectl/#kubectl-install-curl-2

### Dashboard

Try to find a way to display the kubernetes dashbord, you should see something like this :

![Kubernetes dashboard](https://d33wubrfki0l68.cloudfront.net/e6bda94ebf94cc460db5cdc42bbfdb8f95f5f7ce/fd28b/images/docs/ui-dashboard.png)