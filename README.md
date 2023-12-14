# minio-guide

Add Minio Repo:
```bash
helm repo add minio https://charts.min.io/
```

Install Minio:
```bash
helm upgrade -i minio minio/minio  \
  --set rootUser=rootuser \
  --set rootPassword=rootpass123 \
  --set resources.requests.memory=128Mi \
  --set replicas=1
```


