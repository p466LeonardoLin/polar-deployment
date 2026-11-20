# Containers

## Docker Compose:
`docker compose down` removes the containers. Postgres writes its data into the
container's writable layer, which is deleted together with the container. A new
container starts from the clean image, so the book I added was gone
after `down` and `up`.
