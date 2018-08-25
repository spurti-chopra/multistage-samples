FROM alpine:latest
RUN apk update && apk add gcc musl-dev
COPY main.c .
RUN gcc -static -o main main.c

FROM alpine:latest
COPY --from=0 main /usr/bin/main_binary
ENTRYPOINT ["/usr/bin/main_binary"]
