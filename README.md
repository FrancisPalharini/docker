Comandos mais usados no Docker

### Parar e excluir imagens:
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
