# Curso de Kubernetes

## Comandos importantes

```bash
# Lista os nós ativos no cluster
kubectl get nodes
```

```bash
# Lista os pods ativos no cluster
kubectl get pods
```

```bash
# Lista os pods ativos no cluster e fica exibindo seu status
kubectl get pods --watch
```

```bash
# Mostra informações sobre o pod
kubectl describe pod <POD_NAME>
```

```bash
# Criar e colocar para rodar um novo pod
kubectl run <POD_NAME> --image=<DOCKER_IMAGE>
```

```bash
# Aplica um yaml ou json para criação de algo no kubernetes, de form declarativa
kubectl apply -f ./<FILE_PATH>
```