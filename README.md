# EKS-Terraform

## Trouble-shooting

```bash
docker run -d --name netflix2 -p 8082:3000 tirucloud/netflix:latest
docker exec -it netflix2 sh
apk add --no-cache curl
apk add --no-cache net-tools
netstat -tunlp
```
