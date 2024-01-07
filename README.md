# A demo rust web application

using the framework [rocket](https://rocket.rs/v0.5/guide/getting-started/).

## Run

```
cargo run

curl http://localhost:8000/
```

## Build docker image

```
docker build -t hello-rocket -f Dockerfile .
docker run -p 8000:8000 hello-rocket
```

## Load test

```
k6 run ./api-test.js

-- or:
autocannon http://localhost:8000
```
