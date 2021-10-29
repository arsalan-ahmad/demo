## ABOUT
This repository deploys nginx to k8s cluster `cluster-0` in GCP Project `ops-arsalan-ahmad`
 
## USAGE
If you want to make changes to the deployment, make your changes to values.yaml and run the following commands.
- `helm repo add bitnami https://charts.bitnami.com/bitnami`
- `helm upgrade arsalan-nginx bitnami/nginx -f values.yaml`
