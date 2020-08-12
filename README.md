# Microservices app running through docker & kubernets

### Install all dependencies individually

```bash
npm install
```

### Install client dependencies

```bash
cd client
npm install
```

### Run all individually

```bash
npm start
```

### docker commands

```bash
docker build -t  dockerid/client

docker push dockerid/client

docker ps  //prints information abt running containers

docker run dockerid/client (image id)

docker exec -it container_id cmd(ex:sh)
```

### kubernets commands

```bash
kubectl get pods or services or deployments

kubectl delete pod pod_name

kubectl logs  pod_name

kubectl apply -f config-file-name

kubectl exec -it pod_name cmd(ex: sh)
```
