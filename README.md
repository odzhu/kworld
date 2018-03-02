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

### Developer environment
* [Telepresence](https://github.com/datawire/telepresence) - local development against a remote Kubernetes or OpenShift cluster

### Service mesh
* [Istio](https://istio.io) - an open platform to connect, manage, and secure microservices
* [Linkerd](https://linkerd.io) - service mesh from apache
* [Conduit](https://conduit.io) - new service mesh from linkerd makers

### Application tracing
* [Zipkin](https://zipkin.io) - distributed tracing system. 
* [Vizceral](https://github.com/Netflix/vizceral) - WebGL visualization for displaying animated traffic graphs

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
*  [Notary](https://github.com/theupdateframework/notary) project that allows anyone to have trust over arbitrary collections of data
*  [Grafeas](https://grafeas.io) - An open artifact metadata API to audit and govern your software supply chain
*  [OpenSCAP](https://www.open-scap.org) - Security auditing scaning and auditing 

### CI/CD/Workflow
*  Argo
* [brigade](https://brigade.sh) - event driven scripting for K8s
* [kashti](https://brigade.sh/#kashti) - dashboard for brigade
* [Crosscloudci](https://github.com/crosscloudci) - Integrating, testing, and deploying projects within the #CNCF ecosystem across multiple cloud providers

### Identity

*  Guard - Kubernetes Authentication WebHook Server
*  Kube2iam - provides different AWS IAM roles for pods running on Kubernetes

### Proven Kubernetes Distributions
*  Rancher
*  CloudFoundry 
*  Tectonic 
