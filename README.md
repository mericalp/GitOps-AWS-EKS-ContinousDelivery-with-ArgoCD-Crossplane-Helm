# GitOps-AWS-EKS-ContinousDelivery-with-ArgoCD-Crossplane-Helm

# Requirements
To use this project you need the following components:
* eksctl / kind
* argocd (CLI)
* kubeseal
* kubectl
* kubectl crossplane (CLI)
* helm
* aws (CLI)

Here is the global idea of what we will achieve. We will leverage ArgoCD to deploy an  AWS EKS Cluster using a custom Crossplane composition, and deploy applications to this cluster.  In this way, we are using the very same tool for both Infrastructure as Code and Kubernetes application deployments.

