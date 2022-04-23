# spring-boot-docker
this repo demonstrating the use of docker

1) To build new docker image
  run > docker build -f Dockerfile -t spring-boot-docker .
2) To run docker image
  run > docker run -p 8081:8080 spring-boot-docker
3) To stop the running container
  run > docker container stop <container_id>
