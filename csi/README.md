# Attention: this page is NOT maintained any more, CSI driver and doc has been moved to [github.com/Azure/kubernetes-volume-drivers](https://github.com/Azure/kubernetes-volume-drivers/tree/master/csi).

# kubernetes CSI driver on Azure
This directory contains all kubernetes [CSI](https://kubernetes-csi.github.io/docs/Home.html) drivers on azure

| CSI driver | About |
| ---- | ---- |
| [dysk](./dysk) | This driver allows Kubernetes to use [fast kernel-mode mount/unmount AzureDisk](https://github.com/khenidak/dysk) |
| [hostpath](./hostpath) | This driver allows Kubernetes to use hostPath |
