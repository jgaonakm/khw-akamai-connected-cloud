# Kubernetes The Hard Way

This tutorial walks you through setting up Kubernetes the hard way on [Akamai Connected Cloud](https://www.linode.com/), based on [the guide originally created by Kelsey Hightower](https://github.com/kelseyhightower/kubernetes-the-hard-way). The goal is to help you understand how to bring up a Kubernetes cluster manually, i.e., not using a fully-automated command. 

For a ready-to-deploy version, check out [Linode Kubernetes Engine](https://www.linode.com/products/kubernetes/), or the [Getting Started Guides](https://kubernetes.io/docs/setup).


## Copyright

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.


## Target Audience

Kubernetes The Hard Way is optimized for learning, which means taking the long route to ensure you understand each task required to bootstrap a Kubernetes cluster. The target audience for this tutorial is people interested in understanding how the Kubernetes components fits together, either for performing their role better or achieving a certification like CKAD.

> The results of this tutorial should not be viewed as production ready, but don't let that stop you from learning!


## Labs

This tutorial uses [Akamai Connected Cloud](https://www.linode.com/), but the knowledge can be applied to other platforms. **You can [create an account here](https://login.linode.com/signup?promo=docs080123)**

### Cluster Details

Kubernetes The Hard Way guides you through bootstrapping a highly available Kubernetes cluster with end-to-end encryption between components and RBAC authentication. It has been tested with the following versions

* [kubernetes](https://github.com/kubernetes/kubernetes) v1.29.0
* [containerd](https://github.com/containerd/containerd) v1.7.11
* [runc](https://github.com/opencontainers/runc/) v1.1.10
* [cni](https://github.com/containernetworking/cni) v1.4.0
* [etcd](https://github.com/etcd-io/etcd) v3.5.11
* [coredns](https://github.com/coredns/coredns) v1.11.1

### Content

* [Prerequisites](guide/0.prerequisites.md)
* [Provisioning Compute Instances](guide/1.instances.md)
* [Creating the certificates](guide/2.certificates.md)
* [Generating the configuration files](guide/3.configFiles.md)
* [Bootstrapping the Control Plane (part 1)](guide/4.controlPlane-1.md)
* [Bootstrapping the Control Plane (part 2)](guide/4.controlPlane-2.md)
* [Bootstrapping the Worker Nodes](guide/5.workerNodes.md)
* [Configuring networking](guide/6.networking.md)
* [Smoke Test](guide/7.smokeTests.md)
* [Cleaning Up](guide/8.cleanUp.md)

