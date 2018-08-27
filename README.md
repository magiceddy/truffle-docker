# truffle-docker
Docker container for truffle

## Usage

### In truffle-docker container start truffle service
```$ docker-compose run --rm --service-ports --name truffle-container truffle```

### Create your project. Ex:
```$ truffle unbox webpack```

### In case your have an error visitin localhost:8080 change your run config in webpack: Ex:
```"dev": "webpack-dev-server --host 0.0.0.0"```

### and visit http://0.0.0.0:8080/

### Open the container instance in a new terminal
```$ docker exec -it truffle-container bash```