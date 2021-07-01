# KIND cluster with audit log enabled.


## Create cluster

**Please replace the sixth line of the kind.yaml file with your current path**


```
kind create cluster --config kind.yaml
```

then you can just run this command to see audit logs.

```
tail -f audit/audit.log
```
