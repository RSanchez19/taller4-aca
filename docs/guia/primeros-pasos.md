# Primeros Pasos

Esta guía te ayudará a empezar a utilizar nuestra API después de completar la [instalación](instalacion.md).

## Autenticación

Antes de poder utilizar los endpoints de la API, necesitas obtener un token de autenticación.

### Obtener un Token

```bash
curl -X POST http://localhost:8000/api/auth/token \
  -H "Content-Type: application/json" \
  -d '{"username": "tu_usuario", "password": "tu_contraseña"}'
```

Respuesta:

```json
{
  "access_token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...",
  "token_type": "bearer",
  "expires_in": 3600
}
```

Guarda el `access_token` para usarlo en las siguientes solicitudes.

