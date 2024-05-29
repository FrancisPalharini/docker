# docker
comandos usados no Docker

# Parar e excluir imagens:
```sh
docker stop $(docker ps -a -q)
docker rm $(docker ps -a -q)
