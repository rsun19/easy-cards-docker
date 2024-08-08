# Docker Steps:

## Building for production

- `docker-compose -f docker-compose.production.yml build postgres`
- `docker-compose -f docker-compose.production.yml up postgres`
- `docker-compose -f docker-compose.production.yml build --no-cache`
- `docker-compose -f docker-compose.production.yml up -d`

## Building for development (work in progress)

- `docker-compose build --no-cache`
- `docker-compose up -d`