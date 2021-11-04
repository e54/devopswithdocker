FROM alpine as build-env
RUN apk add --no-cache build-base
WORKDIR /app
COPY . .
RUN gcc -o simple simple.c

FROM alpine
COPY --from=build-env /app/simple /app/simple
WORKDIR /app
CMD ["/app/simple"] 
