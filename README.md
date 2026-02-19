# Práctica 4.1: Introducción a CI/CD

Este proyecto implementa un flujo de CI con GitHub Actions y un despliegue manual en AWS EC2 de una aplicación Flask.

## 1. Configuración de AWS
Instancia EC2 activa y configuración de Security Groups (Puerto 8000 abierto).
![AWS Instance](image.png)
![Security Groups](image-1.png)
![Redes](image-2.png)

## 2. Despliegue en la Instancia (SSH)
Preparación del entorno, clonado del repositorio e instalación de dependencias.
![Instalación Herramientas](image-3.png)
![Git Clone](image-4.png)
![Entorno Virtual](image-5.png)
![Instalación Requisitos](image-6.png)

## 3. Ejecución y Verificación
Puesta en marcha del servidor Flask y comprobación de las rutas `/` y `/health`.
![Flask Run](image-7.png)
![Navegador Home](image-8.png)
![Navegador Health](image-9.png)

## 4. Integración Continua (CI)
Validación automática de tests mediante GitHub Actions en cada push.
![Workflow List](image-10.png)
![Unit Tests Success](image-11.png)