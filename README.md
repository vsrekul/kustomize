# kustomize
cd kustomize-apache/base
docker build -t your-docker-repo/apache:latest .
cd ../overlays/production
kubectl apply -k .
kubectl get deployments
kubectl get services

