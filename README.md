# kubernetes-redis-sentinel

```
helm upgrade --install redis-sentinel bitnami/redis --namespace redis --create-namespace 
--set sentinel.enabled=true,volumePermissions.enabled=true,replica.replicaCount=2,auth.enabled=false,master.livenessProbe.enabled=true,master.persistence.size=10Gi,replica.persistence.size=10Gi
```
