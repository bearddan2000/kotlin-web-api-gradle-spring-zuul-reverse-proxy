# kotlin-web-api-gradle-spring-zuul-reverse-proxy

## Description
A springboot app that uses zuul
as a reverse proxy. All requests
to `/api` will be forwarded to nodejs
server.

## Tech stack
- kotlin
- gradle
  - springboot
  - netflix zuul
- nodejs

## Docker stack
- gradle:jdk11
- node:latest

## To run
`sudo ./install.sh -u`
- http://localhost/all
- http://localhost/api/all

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credits
- https://spring.io/guides/gs/routing-and-filtering/
