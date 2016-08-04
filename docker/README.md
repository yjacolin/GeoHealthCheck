# Docker installation

## Build

```
$ cd GeoHealthCheck
$ docker build -t yjacolin/geohealthcheck .
```

## Composition

In the same directory as this Readme file:
```
$ docker-compose up
```

This composition run a GeoHealthCheck application and the cron job needed. 

## Setup

You can change the docker-compose.yml file to adapt the cron frequency and some
environmental variable.
