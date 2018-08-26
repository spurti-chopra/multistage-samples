## To build image with scratch as base
`$ docker build -f Dockerfile.scratch -t go-multi-stage-docker-scratch .`

## To run the container
`$ docker run --rm go-multi-stage-docker-scratch:latest`


## To build image with alpine as base
`$ docker build -f Dockerfile -t go-multi-stage-docker-alpine .`

## To run the container
`$ docker run --rm c-go-multi-stage-docker-alpine`

## Size Difference b/w the two
`go-multi-stage-docker-scratch   latest                 28595ac754a6               2.01MB`

`go-multi-stage-docker-alpine    latest                 275544e35711               6.42MB`
