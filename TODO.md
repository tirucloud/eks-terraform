# TODO

- Update kubeconfig for kubectl access to the EKS cluster (cluster not found, likely already deleted)
- Delete Kubernetes resources (deployment and service) to remove LoadBalancer dependencies (failed due to cluster deletion)
- Run terraform destroy to delete AWS resources (completed after removing lingering security group)
