# Create and Start
docker compose up -d

# Stop and Remove
docker compose down

# Start container only
docker compose start

# Stop container only
docker compose stop

# Tail Logs for all
docker compose logs -f

# Logs for specific container
docker compose logs -f <Container name>