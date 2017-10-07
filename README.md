Simple docker-compise example with apache. 

- Start with `docker-compose -up -d`
- Rebuild image with `docker-compose -up --build -d`
- Use `docker ps -a` to see container names.
- Enter the container with `docker exec -it CONTAINER bash`
- Use `curl CONTAINER` inside the container.