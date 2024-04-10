# Deploy the namespace issue case
kubectl apply -f applicationset.yaml

# Issue
The application is deployed to cnpg-testcase but the clusterolebinding service account is mapped to argocd namespace.  
`kubectl describe clusterrolebinding cnpg-cloudnative-cloudnative-pg`
