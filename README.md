# PGAdmin

Setup your env file:
```
cp .env.example .env
# ...
```

update your credentials and set desired port for HTTP serve.

Launch:
```
docker compose up -d
```

Now you can access pgadmin via http://localhost (or http://localhost:port).
Use same credentials as you provided in `.env` file.


Remove container (if required):
```
docker rm -f pgadmin
```
