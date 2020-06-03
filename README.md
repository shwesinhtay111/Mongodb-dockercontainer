# spring-boot-mongodb
This repository contains a Spring Boot example project for MongoDB.

For a code review of this repo, see my related [blog post](https://springframework.guru/3402-2/).

You can learn more about my courses [here](http://courses.springframework.guru/courses/) on my site.


Create mongodb with docker
===============================
docker run -d mongo

In new cmd tag:

docker run ps

docker run -a ps

docker exec -it container-NAMES bash

docker stop mongo

docker run -p 27017:27017 -d mongo

in chrome,browse localhost:8080


docker ps

docker logs -f CONTAINER ID

docker image inspect mongo

docker images -q --no-trunc


To remove a docker image:

docker rmi <image name>

Delete Untagged(dangling)Images

docker rmi @$(docker images -q if dangling=true)

Delete all images:

docker rmi $(docker images -q)

to remove specified one

docker run --rm image_name

if you want to kill,

docker kill container-Name container-id
