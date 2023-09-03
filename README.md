# Einkaufsliste

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![GitHub last commit](https://img.shields.io/github/last-commit/blueirongirl/einkaufsliste-app)
[![Java CI with Maven](https://github.com/blueirongirl/einkaufsliste-app/actions/workflows/build%20with%20maven.yml/badge.svg?branch=master)](https://github.com/blueirongirl/einkaufsliste-app/actions/workflows/build%20with%20maven.yml)
[![Docker Image CI](https://github.com/blueirongirl/einkaufsliste-app/actions/workflows/docker-image.yml/badge.svg?branch=master)](https://github.com/blueirongirl/einkaufsliste-app/actions/workflows/docker-image.yml)

Dies ist ein Showcase für das Java-Framework Spring Boot in Kombination mit dem TypeScript-Frontend-Framework Angular und PrimeNG.
Die Einkaufsliste kann mit [Docker](Dockerfile) gestartet werden. [GitHub Actions](.github/workflows) sind zusätzlich inkludiert.

## Einkaufsliste starten:

### Maven

```shell
./mvnw package spring-boot:run
```

### Docker

```shell
docker build -t blueirongirl/einkaufsliste-app .
docker run -p 8080:8080 -d --name spring-demo blueirongirl/einkaufsliste-app
```
