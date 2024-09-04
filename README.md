# dockerBasicProject
Containerizing services in a java application. Services include NGINIX, Apache TomCat, RabbitMQ, memcache and MYSQL database. The project utilizes docker-compose to run the multiple containers.
# Create directory
mkdir compose
cd compose/

# docker compose command
docker compose

# Create a docker-compose.yml file for the project
vim docker-compose.yml

# Bring up all the containers
docker compose up -d
docker compose ps
ip addr show
docker compose down

# Go to browser and enter VMIP:80
