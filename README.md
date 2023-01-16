# k8s-kustomize
Deploy to Kubernetes with Kustomize

## deploy all resources
  ### with : 
 - $ kubectl apply -f application/ns.yaml
 - $ kubectl apply -f application/cm.yaml
 - $ kubectl apply -f application/deploy.yaml
 - $ kubectl apply -f application/svc.yaml
  ### OR : 
 - $ kubectl apply -f application/

## to test if the service works well 
 - $ kubectl exec -it pod/{name_pod} -n example -- sh 
 - $ curl {cluster_ip}