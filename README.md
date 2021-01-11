# Containerisation with Docker
## what is Docker?
- Docker is an open-souce platform  **docker hub documentation**
- it helps and enables us to seperate applications from the infrastructure
- it allows us to deliver software faster
- Docker is written in GO language
### why Docker?
- multi billion dollar companies are using or adapting Docker, e.g Ebay, Netflix
- docker adoption is anticipated by 50% by the end of 2020
### Demand and future of Docker
### Docker API

### What is the difference bwtween VM and Docker?
- Docker is light-weight and user friendly 
- Docker shares the resources of OS as opposed to using the OS completely
- Docker engine connects the container with OS and only use the resources required
- Vm works with Hyperviser
 
# Docker commands:
```bash
docker pull name_of_image
docker run name_of_image
docker build -t name_of_image
docker commit name_of_image/container-id
docker start container-id
docker stop rm cotainer-id/name
docker ps and ps -a # to check existing containers

# logging into container
docker exec -it name_of_container/id

```