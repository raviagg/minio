# minio
MinIO service which provides S3 APIs

# Steps to deploy
- Clone this repo
- cd minio
- kubectl apply -f minio-argo-app.yaml
After above steps the argocd should show the minio application. Post that when we do any changes to this repo, those changes will be automatically deployed.
