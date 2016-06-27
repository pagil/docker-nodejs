This repository contains a very basic NodeJS app which is deployed to
DOCKER image created to be deployed to AWS.

Useful commands:

docker run -p 49160:8080 -d vik/centos-node-hello

docker ps

docker build -t vik/centos-node-hello .

docker images

docker stop $(docker ps -a -q)

curl -i localhost:49160
