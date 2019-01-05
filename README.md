# Charts

A collection of charts.

## Terminator

```
helm repo add knabben https://knabben.github.io/charts/
helm install --name terminator terminator
```

This have the following custom resource enabled by default

```
Name:         deploy
Namespace:    default
API Version:  app.terminator.dev/v1alpha1
Kind:         Terminator
Spec:
  Memcache:  false
  Rabbitmq:  false
  Redis:     true
```
