\# Experiment 6 - Dockerfile and DockerHub



\## Build Image

docker build -t redisnew .



\## Run Container

docker run --name myredisnew -d redisnew



\## Check Containers

docker ps



\## Stop Container

docker stop myredisnew



\## Login to DockerHub

docker login



\## Commit Container as Image

docker commit myredisnew YOUR\_DOCKERHUB\_USERNAME/redis1



\## Push Image

docker push YOUR\_DOCKERHUB\_USERNAME/redis1



\## Pull Image

docker pull YOUR\_DOCKERHUB\_USERNAME/redis1



\## Run Pulled Image

docker run --name myredis -d YOUR\_DOCKERHUB\_USERNAME/redis1



\## Access Redis

docker exec -it myredis redis-cli



SET name "Abcdef"

GET name

exit

