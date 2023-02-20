# Instructions

Generate instana operator files and add them with the following commands:

```bash
kubectl instana operator template --output-dir generated
kustomize edit add resource generated/*.yaml 
```
