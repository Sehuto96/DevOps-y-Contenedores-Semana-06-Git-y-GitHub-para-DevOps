# Festival DevOps Music Fest

Proyecto académico para practicar DevOps.

## Tecnologías

- HTML
- CSS
- Python
- Flask
- Docker
- Docker Compose
- Git
- GitHub

## Estructura

```text
frontend/
backend/
docker-compose.yml
README.md
```

## Docker

Construcción:

```bash
docker build -t festival-api .
```

Ejecución:

```bash
docker run -p 5000:5000 festival-api
```

## Control de versiones

Se utilizó Git Flow básico mediante ramas:

- feature-landing
- feature-backend

Repositorio alojado en GitHub.