# Endpoints de la API

Esta sección proporciona documentación detallada sobre todos los endpoints disponibles en la API.

## Resumen de Endpoints

| Método | Endpoint                    | Descripción                            | Requiere Auth |
|--------|-----------------------------|----------------------------------------|:-------------:|
| `POST` | `/api/auth/token`           | Obtiene un token de autenticación      |       No      |
| `POST` | `/api/auth/refresh`         | Refresca un token de autenticación     |       Sí      |
| `GET`  | `/api/recursos`             | Lista todos los recursos               |       Sí      |
| `GET`  | `/api/recursos/{id}`        | Obtiene un recurso por ID              |       Sí      |
| `POST` | `/api/recursos`             | Crea un nuevo recurso                  |       Sí      |
| `PUT`  | `/api/recursos/{id}`        | Actualiza un recurso por ID            |       Sí      |
| `PATCH`| `/api/recursos/{id}`        | Actualiza parcialmente un recurso      |       Sí      |
| `DELETE`| `/api/recursos/{id}`       | Elimina un recurso por ID              |       Sí      |
| `POST` | `/api/recursos/search`      | Realiza una búsqueda avanzada          |       Sí      |
| `GET`  | `/api/usuarios`             | Lista todos los usuarios               |       Sí      |
| `GET`  | `/api/usuarios/me`          | Obtiene el usuario actual              |       Sí      |
| `GET`  | `/api/estadisticas/resumen` | Obtiene un resumen de estadísticas     |       Sí      |

---
