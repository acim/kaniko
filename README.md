# kaniko

Playing with kaniko

## Create Docker Hub push secret

```sh
k create secret generic dockerhub  --from-file=config.json
```
