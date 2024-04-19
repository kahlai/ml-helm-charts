## Helm Charts

Simple charts for

- Label Studio
- Milvus




```
helm package helm-chart-sources/milvus 
helm package helm-chart-sources/label-studio 
```

```
helm repo index . --merge index.yaml --url https://kahlai.github.io/ml-helm-charts/
```
