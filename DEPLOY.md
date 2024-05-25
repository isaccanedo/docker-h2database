docker build -t h2  .

docker tag h2 isac/h2

docker push isac/h2:latest
