# kong-tests-compose

A [docker-compose] file to run [kong]'s integration test suite's dependencies.

The following containers will be created:

- kong-tests-postgres
- kong-tests-redis
- kong-tests-grpcbin

### Usage

```
$ docker-compose up
```

### License

MIT

[docker-compose]: https://docs.docker.com/compose/
[kong]: https://github.com/Kong/kong
