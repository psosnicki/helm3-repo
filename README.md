# Helm Charts

This repository contains packaged Helm charts provided by psosnicki. 

## Add Repository (stable)
`$ helm repo add psosnicki-helm-repo-stable  https://psosnicki.github.io/helm3-repo/stable`   
`$ helm repo update`

## Install Packages (stable)  
`$ helm install my-release psosnicki-helm-repo-stable/k8s-pod-service-account [--version=1.0.0]`  