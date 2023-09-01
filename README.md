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


<img width="676" alt="Screenshot 2023-09-01 at 8 49 33 PM" src="https://github.com/mericalp/GitOps-AWS-EKS-ContinousDelivery-with-ArgoCD-Crossplane-Helm/assets/83503845/558e15ed-50c6-43b2-87c8-095bc2052dcb">



<img width="1660" alt="Screenshot 2023-08-29 at 11 31 50 PM" src="https://github.com/mericalp/GitOps-AWS-EKS-ContinousDelivery-with-ArgoCD-Crossplane-Helm/assets/83503845/82f4cd3d-e7ea-4a78-a6cd-2e6b88cc6c34">

<img width="1434" alt="Screenshot 2023-08-29 at 11 31 27 PM" src="https://github.com/mericalp/GitOps-AWS-EKS-ContinousDelivery-with-ArgoCD-Crossplane-Helm/assets/83503845/cb9fa213-7347-465f-8631-20d7f357ad91">
