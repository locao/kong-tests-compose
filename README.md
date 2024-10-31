# kong-tests-compose

A [docker-compose] file to run [kong]'s integration test suite's dependencies.

The following containers will be created:

- kong-tests-postgres
- kong-tests-redis
- kong-tests-grpcbin

If the `--profile idp` flag is used, the following container will be created:

- kong-tests-keycloak

### Usage

```
$ docker-compose up
```

or

```
$ docker-compose --profile [idp|all] up
```

### License

MIT

[docker-compose]: https://docs.docker.com/compose/
[kong]: https://github.com/Kong/kong
