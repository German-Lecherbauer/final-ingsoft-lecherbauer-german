# Final Ingeniería de Software

Proyecto mínimo desarrollado para el final de la materia Ingeniería de Software.

La aplicación muestra el nombre, apellido y DNI del alumno mediante una página HTML ejecutada dentro de un contenedor Docker.

## Requisitos
- Docker Desktop
- Git

## Estructura del proyecto
- index.html
- Dockerfile
- README.md

## Ejecución del proyecto con Docker

### Construcción de la imagen
```bash
docker build -t final-ingsoft .
```

### Ejecución del contenedor
```bash
docker run -d -p 8080:80 --name final-ingsoft-container final-ingsoft
```

### Acceso desde el navegador
http://localhost:8080
