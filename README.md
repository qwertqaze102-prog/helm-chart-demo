# Helm Chart Demo

Simple Helm chart packaging for a web app:
- values.yaml
- deployment/service templates
- helpers / labels

```bash
helm lint ./charts/demo-web
helm template demo ./charts/demo-web
helm upgrade --install demo ./charts/demo-web -n demo --create-namespace
```
