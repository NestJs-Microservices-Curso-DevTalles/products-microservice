## Product Microservice

## Dev

1. Clonar el repositorio
2. Instalar dependencias
3. Crear un archivo `.env` basado en el `env.template`
4. Levantar servidor de nats 
docker run -d --name nats-main -p 4222:4222 -p 6222:6222 -p 8222:8222 nats
5. Tener levantados los microservicios que se van a consumir
6. Levantar proyecto con ǹpm run start:dev`
