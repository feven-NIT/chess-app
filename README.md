```shell
oc apply -f manifest/chess-app.yaml
oc adm policy add-scc-to-user privileged -z chess-sa -n chess-namespace 
```
