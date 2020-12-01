# helm

### Sample git repo URL
```
https://raw.githubusercontent.com/mohanchaz/helm/master/index.yaml
```
### Add repo 
```
helm repo add <reponame> https://raw.githubusercontent.com/mohanchaz/helm/master/
```

### List helm repo
``
helm repo list
``
### Remove repo
`
helm repo remove <reponame>
`
### To install chart in dry run from git repo
```
helm install <name> moha/mychart --debug --dry-run
```
### To install chart from git repo
```
helm install <name> moha/mychart --debug --dry-run
```
### To remove installed chart

``
helm delete <name>
``
### List installed charts
``
helm ls
``




