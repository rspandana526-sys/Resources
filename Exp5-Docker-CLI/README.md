

\# Experiment 5 - Docker CLI Commands



\## 1. Pull Redis Image

docker pull redis



\## 2. Run Redis Container

docker run --name my-redis -d redis



\## 3. Check Running Containers

docker ps



\## 4. Enter Redis CLI

docker exec -it my-redis redis-cli



\## 5. Store a Value

SET name "Alice"



\## 6. Retrieve a Value

GET name



\## 7. Exit Redis CLI

exit



\## 8. Stop Container

docker stop my-redis



\## 9. Start Container

docker start my-redis



\## 10. Remove Container

docker rm -f my-redis



\## 11. Remove Redis Image

docker rmi redis



