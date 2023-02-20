# Instructions

Generated with the following commands from the `components/instana-operator/base` directory

```bash
kubectl instana operator template --output-dir generated
kustomize edit add resource generated/*.yaml 
```
