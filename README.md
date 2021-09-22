# natcws

### PAT value has been removed

## Commands:

Build Image:
  
  `docker build . -t runner`

Verify image created:

  `docker images`
  
Kubernetes:

`kubectl create ns gitaction
  kubectl apply -f ./secret.yaml
  kubectl apply -f kubernetes.yaml `
  
Verify:

`kubectl -n gitaction get deployment
  kubectl -n gitaction get pods`
  
Scale:

  `kubectl -n gitaction scale deployment runner --replicas=3`
