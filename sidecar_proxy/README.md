# SideCar proxy

Criando deployment
```sh
kubectl apply -f deployment.yaml
```

Criando sidecar proxy
```sh
kubectl label namespace default istio-injection=enabled
```