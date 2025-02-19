
# Docker Odoo 17.0 With PostgreSQL 16
by Angel

Primero instalar docker si no lo tiene
```
apt  install docker.io docker-compose -y
```

Descargar repositorio
```
git clone thttps://github.com/GhostSlayer-maker/odoo17-belephantit-preprod
```

Entrar al directorio
```
cd odoo-17-docker-compose
```
Iniciar docker por cualquiera de las vias que aportan diferentes fucionalidades
```
docker compose up -d
docker compose up -d --build
docker compose up --build
```

Detener odoo
```
docker compose down
```

Sitio local
```
http://localhost:10017/
```

Contraseña maestra de Odoo:
```
minhng.info
```
