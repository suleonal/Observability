Burada bir kubernetes kumesi icinde prometheus kurulumu icin gerekli dosyalar bulunmaktadir. 

Kurulum sonrasinda, calisan prometheus'un servis portlarindan, port-forwarding ile durumu gorulebilir.

```
cd Prometheus
kubectl create -f . -n observability
```