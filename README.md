# Sistema de Seguimiento Correos

Sistema automático de seguimiento de envíos de Correos de España.

## Despliegue con Docker

1. Clona el repositorio
2. Copia `.env.example` a `.env` y configura tus credenciales
3. Ejecuta: `docker-compose up -d`

## Variables de Entorno Requeridas

- `CORREOS_CLIENT_ID`: Client ID de la API de Correos
- `CORREOS_CLIENT_SECRET`: Client Secret de la API de Correos
