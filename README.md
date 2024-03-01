XRAY SERVER DOCKER COMPOSE

dont forget to change ./nginx/nginx.conf based on your domain
```bash
server_name your.domain.com;
```

and also add account under ./xray/config.json
```bash
client: [
  ....
]
```
