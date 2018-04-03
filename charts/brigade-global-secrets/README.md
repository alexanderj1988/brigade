# Brigade Global Secret

This is the Brigade Global Secret chart. Use it to create or update Brigade global secret, which will be available in every pipeline.

Usage:

```
$ helm inspect values brigade/brigade-global-secrets > myvalues.yaml
$ # Edit myvalues.yaml
$ helm install brigade/brigade-global-secrets -n brigade-global-secrets -f myValues.yaml
```

To read documentation on the configurable parameters, run:

```
$ helm inspect values brigade/brigade-brigade-global-secrets
```
