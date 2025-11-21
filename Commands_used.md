### Access keys are setup as rotated manner, so everytime it will change

## To check version - SERVER - K8s version, Client - Our local machine 

```
[root@lvsdevmahileshsbx01 ~]# kubectl version
Client Version: v1.29.3
Kustomize Version: v5.0.4-0.20230601165947-6ce0bf390ce3
'Server Version: v1.33.5-eks-3cfe0ce'
WARNING: version difference between client (1.29) and server (1.33) exceeds the supported minor version skew of +/-1
```

## To use kubectl as alias for easy command execution

```
aws eks update-kubeconfig --name <cluster_name> --region <region_name> --profile <aws_account_name>

Ex:- aws eks update-kubeconfig --name rom-usw2-dev --region us-west-2 --profile rom-npd-dev
```

