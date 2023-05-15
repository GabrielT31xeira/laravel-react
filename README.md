# Comando Base
```
docker compose build --no-cache && docker compose up --force-recreate

```
## Porta Backend Nginx (Descomentar no docker compose)
```
localhost:8083

```
## Porta Backend Laravel
```
localhost:8000

```
## Porta Frontend
```
localhost:3000

```

- OBS.: Para rodar com o nginx em produção lembra de descomentar o container do nginx no arquivo ```docker-compose.yaml```