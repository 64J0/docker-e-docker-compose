# leaderboard-redis

Este repositório foi clonado de um projeto do pellizzetti que trabalhar na Rocketseat lidando com devOps.

O conteúdo foi apresentado na aula gravada e disponível na plataforma do bootcamp da Rocketseat chamado Docker & Docker Compose.

Alguns comandos executados durante a vídeo-aula:

```bash
  # run the docker service
  docker run --name leaderboard-redis -e REDIS_PASSWORD=redis123 -d -p 6379:6379 bitnami/redis:latest

  # build the Dockerfile
  docker build -t leaderboard-api .
```
