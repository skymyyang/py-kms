# Usage
```
kubectl apply -f k8s-py3-kms.yaml
```
Make sure that the environment you are using supports "loadbalancer"; if not, you can modify the "service" field in the "k8s-py3-kms.yaml" file and use "nodeport".