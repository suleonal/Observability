## Loki ve Promtail kurulumu
Sadece loki ve promtaili varsayilan degerleri ile kurmak icin asagidaki adimlari uygulayin:
```
helm repo add grafana https://grafana.github.io/helm-charts
```

```
helm install loki grafana/loki-stack --namespace=observability
```
