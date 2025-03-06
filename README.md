# Cribldocker

This yaml script will deploy a small Cribl Cluster. One Network for Containers to communicate. 

Install Docker

https://docs.docker.com/get-docker/

Install Docker Compose

https://docs.docker.com/get-started/08_using_compose/

Copy yaml script to your system with Docker & Docker Compose Installed

docker compose up -d --scale workers=<How Many workers do you want>


*****
The Kube file is if you want to run the workers in a Kubernetes 
