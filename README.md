# dc-n8n

Docker Compose n8n

```
cp .env.example .env
vi .env
```

```
docker network create --driver bridge back-n8n
docker-compose build
docker-compose up -d
```