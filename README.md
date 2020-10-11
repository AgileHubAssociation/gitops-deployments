# deployments

Deploying apps with ArgoCD, using App of Apps pattern
The root application needs to be applied manually


* kubectl config use-context kind-argocd-cluster --namespace argocd
* kubectl apply -f root/root-app.yaml