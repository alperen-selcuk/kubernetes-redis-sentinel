# kubernetes-redis-sentinel

helm upgrade --install redis-sentinel bitnami/redis --namespace redis --create-namespace --set sentinel.enabled=true
