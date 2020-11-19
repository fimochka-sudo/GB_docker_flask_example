# python-flask-docker
Basic Python Flask app in Docker which prints the hostname and IP of the container

### Build application
Build the Docker image manually by cloning the Git repo.
```
$ git clone https://github.com/fimochka-sudo/GB_docker_flask_example.git
$ docker build -t fimochka/gb_docker_flask_example .
```

### Download precreated image
You can also just download the existing image from [DockerHub](https://hub.docker.com/r/fimochka/gb_docker_flask_example/).
```
docker pull fimochka/gb_docker_flask_example
```

### Run the container
Create a container from the image.
```
$ docker run -d -p 8180:8180 -p 8181:8181 fimochka/gb_docker_flask_example
```
