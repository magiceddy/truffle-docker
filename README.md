# truffle-docker
Docker container for truffle

## Usage

### Start truffle service
```$ docker-compose run --name truffle-container truffle```

### Create app folder and move in it
```$ mkdir app && cd app```

### Create your project. Ex:
```$ truffle unbox webpack```


### In order to attach a terminal to the running container you need the container's ID or Name

### attach the terminal
```$ docker attach truffle-container```
