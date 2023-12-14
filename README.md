# minio-guide

Add Minio Repo:
```bash
helm repo add minio https://charts.min.io/
```

Install Minio:
```bash
helm upgrade -i minio minio/minio  \
  --set rootUser=rootuser \
  --set rootPassword=rootpass123
```


