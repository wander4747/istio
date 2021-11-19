# Addons

Prometheus

```sh
kubectl apply -f prometheus.yaml
```

Kiali

```sh
kubectl apply -f kiali.yaml
```

Grafana

```sh
kubectl apply -f grafana.yaml
```

Jaeger

```sh
kubectl apply -f jaeger.yaml
```

### Acessando Kiali Dashboard

```sh
istioctl dashboard kiali
```