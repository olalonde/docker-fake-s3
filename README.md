# docker-fake-s3

Fake AWS S3 server for local development based on [fake-s3](https://github.com/jubos/fake-s3). Runs in docker.

Usage (in docker-compose.yml):

```
fakes3:
  image: olalond3/fakes3
  ports:
    - "4567:4567"
```

See [fake-s3](https://github.com/jubos/fake-s3)