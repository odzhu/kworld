# kworld (WIP)
A curated list of kubernetes projects worth watching, yet another.
-----------------------------------------------------------------------

Projects
=======================================================================

### Install

* [Bootkube](https://github.com/kubernetes-incubator/bootkube) - CoreOS self hosted k8s installer, probably the simplest way to maintain cluster lifecycle is to use k8s paradigms and objects.  
* [Rke](https://github.com/rancher/rke) - Rancher's command line cluster management.

### Cluster admin
* [Kubeapps](https://github.com/kubeapps/kubeapps) - integrated monocular helm dashboard + tiller.
* [Monocular](https://github.com/kubernetes-helm/monocular) - helm web UI, usefull for making corporate package registry.

### Integration
* [Voyager](https://github.com/appscode/voyager) - Secure HAProxy Ingress Controller.
* [Service catalog](https://github.com/kubernetes-incubator/service-catalog) - integration via [OSB](https://www.openservicebrokerapi.org)* [Brigade](https://github.com/Azure/brigade) - k8s event driven programing in js

### Workloads
* [Draft](https://github.com/Azure/draft) - simple CI for dev purposes
* [Spinnaker](https://github.com/spinnaker/spinnaker) - cross-cloud continuous deployment.
* Contour - envoy ingress controller

### Service mesh
* Istio
* Linkerd - the old school.
* conduit

### Packages
*  Helm - package managing
*  Helmfile
*  Landscaper
*  Aptomi - helm + ksonnet framework + holistic management

### Monitoring
*  Heapster -enables grafs on kubernetes dashboard, very useful ; comes with influx-grafana ;  installed with heapster on minikube
*  Grafana- installed with heapster on minikube
*  Prometheus operator  from CoreOS
*  Cortex - Cortex from weave 

### Storage

*  Stash - backup kubernetes volumes

### Security
*  notary project that allows anyone to have trust over arbitrary collections of data

### CI/CD/Workflow
*  Argo

### Identity

*  Guard - Kubernetes Authentication WebHook Server
*  Kube2iam - provides different AWS IAM roles for pods running on Kubernetes

### Proven Kubernetes Distributions
*  Rancher
*  CloudFoundry 
*  Tectonic 
