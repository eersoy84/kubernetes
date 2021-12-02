#### ARGO CD Installation
## namespace ##
kubectl create namespace argocd

## crd files ## 
## namespace argocd must be applied ##

## apply ## 

kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml

## delete ## 

kubectl delete -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml