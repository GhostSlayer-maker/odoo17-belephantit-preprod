
# Docker Odoo 17.0 With PostgreSQL 16
by Angel

First install docker-compose
```
apt  install docker.io docker-compose -y
```

Download repository
```
git clone https://github.com/GhostSlayer-maker/odoo-17-docker-compose.git
```

Lift docker
```
cd odoo-17-docker-compose
docker compose up -d
docker compose up -d --build
docker compose up --build
```

Stop Odoo
```
docker compose down
```

Odoo master password:
```
minhng.info
```