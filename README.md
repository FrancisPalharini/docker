Comandos mais usados no Docker

### Parar e excluir containers:
```sh
docker stop $(docker ps -a -q)
docker rm $(docker ps -a -q)
```

### Listar Imagens
```sh
docker images
```

### Listar containers em execução e parados
```sh
docker ps -a
```

### Excluir todas as imagens:
```sh
  docker rmi $(docker images -q)
```
