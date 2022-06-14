# Arquitectura Docker

## Iniciar el Proyecto
Clonar el repositorio
```
git clone https://gitlab.com/ayd2-g8/arquitectura-docker
```

Crear archivo de variables de entrono DEV.env
```
PORT = numero_puerto
HOST = ''
BDPASS = ''
DATABASE = ''
APP_ENV = ''
TOKEN_SECRET=''
REDIS_PASS = ''
REDIS_HOST = ''

# Variales de entorno para ambiente de producción
GHOST = ''
GPASS = ''
```
Ejecutar el siguiente comando
```
docker-compose up -d --timeout 600
```
