# helm-sso

it's my way of extending an existing stable helm chart with just what I need

it leverages the requirements.yaml file

```
$ argocd app create -f argocd.yaml
```
> WARNING: (you need your own custom version of <br/>
> argocd.yaml and values.yaml to get this really working)

Also, you won't go far without an Ingress or a VirtualService