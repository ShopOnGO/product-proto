# product-proto
Для генерации файлов:
protoc --proto_path=./proto --go_out=./pkg/service --go_opt=paths=source_relative --go-grpc_out=./pkg/service --go-grpc_opt=paths=source_relative proto/common.proto 
protoc --proto_path=./proto --go_out=./pkg/service --go_opt=paths=source_relative --go-grpc_out=./pkg/service --go-grpc_opt=paths=source_relative proto/variants.proto
