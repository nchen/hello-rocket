# A demo rust web application

using the framework [rocket](https://rocket.rs/v0.5/guide/getting-started/).

## Run

```
cargo run
```

## Load test

```
k6 ./api-test.js

-- or:
autocannon http://localhost:8000
```
