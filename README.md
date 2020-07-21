# dokku-docker-load-command

A simple [Dokku](https://github.com/dokku/dokku) plugin that exposes [`docker load`](https://docs.docker.com/engine/reference/commandline/load/) command. This is helpful when using Dokku's [Docker Image Tag Deployment](http://dokku.viewdocs.io/dokku/deployment/methods/images/).

## Installation
```
dokku plugin:install https://github.com/Yihao-G/dokku-docker-load.git
```

## Usage
```
dokku docker load [OPTIONS]
```

To learn more about the available options, see [`docker load`](https://docs.docker.com/engine/reference/commandline/load/) command.

## License
MIT
