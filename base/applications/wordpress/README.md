# Kubernetes.io sample stateful Wordpress app

## Pre-req
- cert-manager installed on the cluster
- Contour ingress installed and configured on the cluster. 
- Envoy service L4 loadbalancer 

This example uses kustomzation spec to onboard a basic wordpress and mysql app. This app is then exposed on 443 using the HTTPProxy resource. 

Modify the `kustomization.yaml` file to modify your settings. 
