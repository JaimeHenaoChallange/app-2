# App 2

Esta es una aplicación de ejemplo desplegada en Kubernetes usando ArgoCD.

## Estructura del Proyecto

- **Docker/**: Contiene el Dockerfile para construir la imagen de la aplicación.
- **Kubernetes/**: Manifiestos de Kubernetes para desplegar la aplicación.
- **.github/workflows/**: Workflows de GitHub Actions para automatizar tareas de CI/CD.
- **doc/**: Documentación adicional.
- **logo-argocd.png**: Logo de ArgoCD utilizado en la documentación.

## Despliegue

1. Construir la imagen Docker:
   ```bash
   docker build -t tu-usuario/app-1:latest .
