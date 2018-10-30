# Postgres container with Postgis

Docker image with postgres instance including the postgis extension.
Superuser is build/build.

## Build container

```
docker build . -t milieuinfo/postgres:<version>
```

## Run container

```
docker run -d -p 5432:5432 milieuinfo/postgres:<version>
```

## Connect to Postgres

```
psql -h localhost -U build
```
