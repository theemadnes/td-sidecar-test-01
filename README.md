# td-sidecar-test-01
testing use of TD sidecars using GKE

### setup 

```
kubectl create ns frontend
kubectl create ns backend 

kubectl -n backend apply -k backend
```