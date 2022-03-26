# k8s-simple-project-with-kong
Tutorial

- Example directory structure project kubernetes with kong and namespacing
- Example use configmap & secret

### 1. Install Kong Gateway (OSS) on Kubernetes native
   ```bash
   kubectl apply -f https://bit.ly/kong-ingress-dbless
   ```
### 2. Create Namespace
   ```bash
   kubectl create namespace production
   kubectl create namespace staging
   ```


   source: https://docs.konghq.com/gateway/2.8.x/install-and-run/kubernetes/

