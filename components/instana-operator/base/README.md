# Instructions

Generate instana operator files and add them with the following commands:

```bash
kubectl instana operator template --namespace=instana-operator --values=values-for-kubectl-instana.yaml --output-dir generated
kustomize edit add resource generated/*.yaml 
```
