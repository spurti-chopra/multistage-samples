## To build image with scratch as base
`$ docker build -f Dockerfile.scratch -t c-multistage-scratch`

## To run the container with above image
`$ docker run --rm c-multistage-scratch:latest`


## To build image with alpine as base
`$ docker build -f Dockerfile -t c-multistage-alpine`

## To run the container with above image
`$ docker run --rm c-multistage-alpine:latest`

## Size Difference b/w the two
`c-multistage-scratch            latest                 d50acdea715d        82.7kB`

`c-multistage-alpine             latest                 a9680fe174d9        4.5MB`
