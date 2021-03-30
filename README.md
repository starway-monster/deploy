# deploy

This is a Continuous Deployment & Continuous Delivary perository.

> Our continuous delivery uses **"argoCD"** and keeps track of the **"master"** directory in the **"deploy"** repository. The development application configuration for **"argoCD"** is located at **deploy/hackatom/app.yaml**. Any changes made to the **hackatom** directory of the deploy repository will be reflected on the development server.

> Kubernetes secrets located at *./secrets/hackatom-secret.yaml*. You can apply this secrets by: `kubectl apply -f ./secrets/hackatom-secret.yaml`

ArgoCD getting started - [https://argoproj.github.io/argo-cd/getting_started](https://argoproj.github.io/argo-cd/getting_started)