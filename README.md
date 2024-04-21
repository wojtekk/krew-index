# wojtekk's krew-index

[Krew](https://krew.sigs.k8s.io/) index repository with my plugins

## Install repository

```bash
kubectl krew index add wojtekk https://github.com/wojtekk/krew-index
```

## List available plugins

```bash
kubectl krew search wojtekk
```

## Install plugins

```bash
kubectl krew install wojtekk/aws-rds-proxy
```
