# erpnext-coolify-deployment
Deployment Docker Compose - Coolify - VPS


# ERPNext Deployment with Coolify

Este repositorio contiene una configuración optimizada para desplegar [ERPNext](https://erpnext.com/) utilizando [Coolify](https://coolify.io/), una herramienta de autohospedaje para servidores. El proyecto incluye un archivo `docker-compose.yml` que configura todos los servicios necesarios para ejecutar ERPNext en un VPS.

## Características
- Despliegue completo de ERPNext versión 14.
- Configuración ajustada para evitar reinicios innecesarios de contenedores.
- Uso de Coolify para gestionar el despliegue en un servidor.
- Servicios incluidos: backend, frontend, base de datos (MariaDB), Redis, colas de trabajo, scheduler y WebSocket.

## Requisitos
- Un VPS con Docker y Docker Compose instalados.
- Coolify configurado en el servidor.
- Conocimientos básicos de Docker y gestión de servidores.

## Instalación
1. Clona este repositorio
2. Configura las variables de entorno en Coolify (ver archivo env "Variables de Entorno").
3. Despliega el proyecto "Deploy"
4. Esperar y Accede a ERPNext en http://<tu-ip>:8081.
5. Nota: Cambie las contraseñas por valores seguros antes de usar en producción.


## Créditos
Este proyecto se basa en ERPNext, una plataforma ERP de código abierto desarrollada por Frappe Technologies. ¡Gracias a ellos por su increíble trabajo!
Inspirado en la documentación oficial.

Basado en el Repositorio:: [Websoft9test](https://github.com/Websoft9test/docker-erpnext/blob/main/docker-compose.yml)


