# store_pb

```zsh
go get google.golang.org/grpc

# 以下は、Dockerfileで入れてる
go install google.golang.org/protobuf/cmd/protoc-gen-go@latest
go install google.golang.org/grpc/cmd/protoc-gen-go-grpc@latest
```

```zsh
protoc --go_out=./ --go-grpc_out=./ proto3/*.proto
```
