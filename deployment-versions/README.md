Criando deployment
```sh
kubectl apply -f deployment.yaml
```

Testar loadbalancer
```sh
while true; do curl http://localhost:8000; echo; sleep 0.5s; done;
```