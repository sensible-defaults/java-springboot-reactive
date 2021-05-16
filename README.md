# Java SpringBoot Reactive

This application builds upon the idea of Sensible Defaults and
generates a Java reactive application with SpringBoot. Like all
Sensible Defaults this is a containerized application and it
uses Docker as its platform.

## Technologies

* Java 11
* Springboot
* Spring WebFlux
* Mongo DB

## How to run it

1. Build it
```shell
$ docker compose build
```
2. Run it
```shell
$ docker compose up
```

3. Hit Spring's actuator to see if everything is live.
```shell
$ curl http://localhost:8080/actuator/
```

## Architectural Decision Records
Reactive applications are usually good for event-driven architectures on
microservices.

## What is this good for
## ...