# docker-app-demo


### Pull docker images

1. :thinking: **Optional:** To speed up following steps, docker images may be pulled in advance.
   Example:

    ```console
    sudo docker pull bitnami/minideb:stretch
    sudo docker pull bitnami/rabbitmq:3.7.16
    sudo docker pull jbergknoff/postgresql-client:latest
    sudo docker pull postgres:11.3
    sudo docker pull senzing/entity-search-web-app:1.0.2
    sudo docker pull senzing/init-container:1.3.0
    sudo docker pull senzing/mock-data-generator:1.1.0
    sudo docker pull senzing/phppgadmin:1.0.0
    sudo docker pull senzing/senzing-api-server:1.7.2
    sudo docker pull senzing/stream-loader:1.2.0
    sudo docker pull senzing/yum:1.1.0
    ```

## XXX

1. XXX

    ```console
    export DOCKER_APP="docker-app"
    ```

## XXX

1. XXX

    ```console
    ${DOCKER_APP} render \
      --parameters-file example.parameters \
      senzing-demo.dockerapp \
      | docker-compose -f - up
    ```

1. Bring down.
   Example:

    ```console
    ${DOCKER_APP} render \
      --parameters-file example.parameters \
      senzing-demo.dockerapp \
      | docker-compose -f - down
    ```


## XXX

1. XXX

    ```console
    docker app render \
      --output docker-compose.yml
      hello-world.dockerapp
    ```

## References

1. Docker app
    1. [GitHub](https://github.com/docker/app)
    1. [Working with Docker App](https://docs.docker.com/app/working-with-app/)
    1. [CLI documentation](https://docs.docker.com/engine/reference/commandline/app/)
1. Cloud Native Application Bundle
    1. [Web site](https://cnab.io/)
