create container postgres

docker run --name database -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres

docker start mongobarber
docker start postgres
docker start redisbarber
