## CI Pipeline Project

# Entrega Pipeline CI Tecnologías Web 24-25

Este repositorio contiene un pipeline CI/CD para una aplicación web construida con Node.js y Docker. El pipeline realiza:
1. Análisis estático del código con ESLint.
2. Ejecución de pruebas unitarias y de integración.
3. Construcción de una imagen Docker y subida al GitHub Container Registry (GHCR).
4. Despliegue automático en un servidor remoto con validación post-despliegue.

## Integrantes del equipo
1. Alumno 1 - Sergio Ferreira Garcel | UO278594
2. Alumno 2 - Diego Martínez Ariznavarreta | UO283436

## Requisitos
- Node.js y Docker configurados localmente.
- Servidor remoto con Docker instalado.

## Configuración
1. Añade estos secretos al repositorio:
   - `DEPLOY_HOST`: Dirección IP del servidor.
   - `DEPLOY_USER`: Usuario SSH.
   - `DEPLOY_KEY`: Clave privada SSH.
   - `GITHUB_TOKEN`: Generado automáticamente por GitHub.
2. Eservidor remoto debe tener acceso al puerto configurado (3000).
