## start

```shell
helm dependency update
helm upgrade -n nifi-dev --create-namespace --install nifi . -f values.dev.yaml
```