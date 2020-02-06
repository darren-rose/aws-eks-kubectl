# aws-eks-kubectl

### update ~/.kube/config
```
aws-vault exec <aws-profile> -- aws eks update-kubeconfig --name <cluster-name> 
```

### use kubectl
```
aws-vault exec <aws-profile> -- kubectl get svc
```

### ecr login
```
$(aws-vault exec <aws-profile> -- aws ecr get-login --no-include-email --region <region-name>)
```
