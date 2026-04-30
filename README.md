# CI/CD Pipeline con Jenkins

**Estudiante:** Damy Villegas  
**Código:** A00398942  

## Objetivo

Automatizar el ciclo de vida del software desde la integración del código hasta su despliegue, garantizando calidad y seguridad en cada etapa.

## Etapas del Pipeline

1. **Build**
   - Construcción del proyecto
2. **Static Analysis (SonarQube)**
   - Análisis de calidad del código
3. **Quality Gate**
   - Validación de estándares de calidad
4. **Docker Build**
   - Construcción de la imagen del sistema
5. **Security Scan (Trivy)**
   - Análisis de vulnerabilidades
6. **Deploy**
   - Despliegue de la aplicación

## Tecnologías utilizadas

- Jenkins
- Docker (simulado)
- SonarQube (simulado)
- Trivy (simulado)
- GitHub

## Flujo de trabajo

Cada vez que se realiza un cambio en el repositorio, Jenkins ejecuta automáticamente el pipeline, validando el código antes de su despliegue.

## Resultados

Se logró implementar un pipeline funcional que demuestra el proceso de CI/CD, asegurando calidad, seguridad y automatización.

## Nota

Debido a limitaciones del entorno (Jenkins ejecutándose en contenedor Docker sin herramientas adicionales como Maven o Docker interno), algunas etapas fueron simuladas para demostrar el flujo completo del pipeline.
