```yaml:provisioning
oc patch provisioning provisioning-configuration --type merge -p '{"spec":{"watchAllNamespaces": true }}'
```

```
oc apply -f cluster-host-namespace.yaml
```
