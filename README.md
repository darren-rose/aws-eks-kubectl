# aws-eks-kubectl

### update ~/.kube/config
```
aws-vault exec <aws-profile> -- aws eks update-kubeconfig --name <cluster-name> 
```

### use kubectl
```
aws-vault exec tvlab_dev -- kubectl get svc
```
