# Vue.js Project Setup with Storybook and Docker

## Helpful Commands

### docker

#### start docker container
```shell
$ docker-compose up -d
```

#### stop docker container
```shell
$ docker-compose stop
```

#### remove docker container
```shell
$ docker-compose down
```

#### log in to running docker container
```shell
$ docker exec -it docker-node--gulp-example_node_1 bash
```

#### view docker containers
```shell
$ docker ps -a
```

### vue

#### Compiles and hot-reloads for development
http://localhost:8080
```shell
$ npm run serve
```

#### Compiles and minifies for production
```shell
$ npm run build
```

#### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

#### vue cli

Convenient way to start the vue dev and storybook servers

##### vue ui
http://localhost:8000
```shell
$ vue ui -H 0.0.0.0
```

### storybook

#### Start dev server
http://localhost:6006
```shell
$ npm run storybook
```

#### Build storybook for production
```shell
$ npm run build-storybook
```
