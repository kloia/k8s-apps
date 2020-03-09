# HPA Testing

* Create load via HPA : 

```
kubectl exec -it fortio-deploy-7cb865f87f-k2c58 /usr/bin/fortio -- load -c 30 -qps 0 -n 3000000 -loglevel Warning http://dotnet-app
```

