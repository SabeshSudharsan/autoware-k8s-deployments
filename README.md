## About These Manifests

These Kubernetes YAMLs are a direct export of my local k8s-based Autoware setup—no special templating, just exactly what I ran on my VM. They serve purely as a reproducible backup and starting point for anyone looking to deploy Autoware in Kubernetes.

### Apply all Kubernetes manifests in this repository
kubectl apply -f

### Verify your Autoware pods are rolling out
kubectl get pods -w 
