## To build image multi-stage image
`$ docker build -f Dockerfile -t java-multistage-alpine .`

## To run the container
`$ docker run --rm java-multistage-alpine:latest`


## Size Difference b/w the the image built using multistage and one using full blown jdk
`java-multistage-alpine          latest                 0121da726f7a              108MB`

`java-jdk-alpine                 latest                 8c3d85de28c0              145MB`
