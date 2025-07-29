1. kubectl get pods
2. kubectl get namespace
3. kubectl config view
4. kubectl config use-context ${name}
5. kubectl config set-context --current --namespace paper-development
6. kubectl config set-context --current --namespace paper-staging
7. kubectl config set-context --current --namespace paper-production
8. kubectl exec -ti ${pods_name} -- /bin/bash
9. gcloud container clusters get-credentials paper-dev-cluster-01 --zone asia-southeast2-a --project paper-development
10. gcloud container clusters get-credentials paper-dev-autopilot --region asia-southeast2 --project paper-development
11. gcloud container clusters get-credentials paper-prod-cluster --zone asia-southeast2-a --project paper-production
12. gcloud container clusters get-credentials paper-staging --zone asia-southeast2-a --project paper-staging-288812
13. kubectl rollout restart deployment/paper-bromo-mq -n paper-production
14. $env:NODE_OPTIONS="--max-old-space-size=8192"; ng serve -c prod-test