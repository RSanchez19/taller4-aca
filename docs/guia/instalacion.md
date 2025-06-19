# Guía de Instalación

Esta guía te mostrará paso a paso cómo instalar y configurar nuestra API en tu entorno local.

## Requisitos del Sistema

- Python 3.8 o superior
- pip (gestor de paquetes de Python)
- Git (para clonar el repositorio)

## Instalación

### 1. Clonar el Repositorio
```bash
git clone https://github.com/odinia/wallet-api.git
cd wallet-api
```

### 2. Entorno Virtual
=== "Windows"
    ```bash
    python -m venv venv
    venv\Scripts\activate
    ```
=== "macOS & Linux"
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

### 3. Instalar Dependencias
```bash
pip install -r requirements.txt
```

### 4. Configurar y Ejecutar
```bash
# Copia el archivo de configuración
cp config.example.ini config.ini

# Inicializa la base de datos
python manage.py init_db

# Ejecuta el servidor
python manage.py runserver
```

!!! warning "Entorno de Desarrollo"
    La configuración y los ejemplos proporcionados están diseñados únicamente para un **entorno de desarrollo local**.