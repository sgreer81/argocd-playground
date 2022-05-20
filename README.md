# argocd-playground


`kubectl create ns argocd`
`kubectl create ns argo-rollouts`

`helm repo add argo https://argoproj.github.io/argo-helm`

`helm install argocd argo/argo-cd -n argocd -f ./argo-setup/argocd-values.yaml`
`helm install argo-rollouts argo/argo-rollouts -n argo-rollouts`

`kubectl apply -f ./applications`