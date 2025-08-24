# nginx-gateway

## install

```shell
# install crds
kubectl kustomize "https://github.com/nginx/nginx-gateway-fabric/config/crd/gateway-api/standard?ref=v2.1.0" > custom-resources.yaml
```