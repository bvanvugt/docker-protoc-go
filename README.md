# docker-protoc-go
docker-protoc-go

### Usage
```sh
docker run -it --rm \
    -v "$PWD":/src \
    -w /src \
    bvanvugt/protoc-go \
    protoc --go_out=plugins=grpc:. *.proto
```
