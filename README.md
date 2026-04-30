# Pipeline CI/CD con Jenkins

Nombre: Damy Yuriana Villegas Ordoñez 
Codigo: A00398942

Este proyecto implementa un pipeline de integración continua utilizando Jenkins.

## Etapas

- Build: construcción del proyecto
- Análisis estático: validación de calidad
- Quality Gate: control de calidad
- Docker Build: construcción de imagen
- Security Scan: análisis de vulnerabilidades
- Deploy: despliegue de la aplicación

## Tecnologías

- Jenkins
- Docker (simulado)
- SonarQube (simulado)
- Trivy (simulado)

## Flujo

El pipeline se ejecuta automáticamente tras cambios en el repositorio, garantizando calidad antes del despliegue.

## Nota

Debido a limitaciones del entorno, algunas etapas fueron simuladas para demostrar el flujo completo CI/CD.