#  Kubernetes Demo

## Temporary interactive shell 
```
kubectl run my-shell --rm -it -n demo --image ubuntu -- bash
```
## Run local instance with skaffold
```
skaffold dev --port-forward
```

## Debug Skaffold output
```
skaffold dev --port-forward -v debug
```