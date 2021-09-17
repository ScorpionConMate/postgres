# Postgres con PGAdmin

- En primer lugar, vamos a crear nuestro archivo de configuracion con:
```bash
cp .env.template .env
```
- En el archivo .env vamos a definir nuestro usuario y contraseña, las variables son `POSTGRES_USER` y `POSTGRES_PASSWORD`

- Una vez configurado el archivo `.env`, procedemos a levantar los servicios con:
```bash
docker-compose up -d
```
