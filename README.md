# Práctica de Servidor Web Nginx con Docker Compose

Repositorio creado para la configuración y despliegue de un servidor web local utilizando **Nginx** gestionado mediante **Docker Compose** y volúmenes mapeados.

## 🚀 Contenido del Proyecto
- **`src/index.html`**: Página web principal con diseño moderno y responsivo ("Hola Mundo").
- **`docker-compose.yml`**: Archivo de configuración que define el servicio de Nginx, el mapeo de puertos (`8080:80`) y el volumen sincronizado en tiempo real.

## ⚙️ Instrucciones de Ejecución
1. Clona este repositorio en tu computadora.
2. Asegúrate de tener Docker y Docker Compose instalados.
3. Ejecuta el siguiente comando en la raíz del proyecto para levantar el servidor:
   ```bash
   docker compose up -d
4. Abre tu navegador web e ingresa a: 
    ```bash 
    http://localhost:8080