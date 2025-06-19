# API de Odinia Wallet

Documentación oficial de la API de Odinia, una wallet virtual para la gestión de activos digitales.

![Odinia Wallet](img/La_billetera_virtual.jpg)

=== "Descripción"

Esta API permite integrar las funcionalidades de Odinia en aplicaciones de terceros de manera segura y eficiente.

## Características Principales

- Gestión de cuentas y balances
- Transferencias entre usuarios
- Soporte para múltiples criptomonedas
- Autenticación segura mediante JWT
- Notificaciones de transacciones

## Inicio Rápido

```bash
# Instalar dependencias
pip install -r requirements.txt

# Iniciar el servidor
python app.py
```

## Estructura del Proyecto

```
proyecto/
├── app.py           # Punto de entrada principal
├── config/          # Configuraciones del proyecto
├── controllers/     # Controladores para manejar solicitudes
├── models/          # Modelos de datos
├── services/        # Servicios y lógica de negocio
└── tests/           # Pruebas unitarias y de integración
```

## Enlaces Útiles

- [Guía de instalación](guia/instalacion.md)
- [Primeros pasos](guia/primeros-pasos.md)
- [Referencia de la API](api/endpoints.md)
