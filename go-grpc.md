gRPC installation

1. Protocol buffers
https://github.com/protocolbuffers/protobuf/releases
cd protobuf
./autogen.sh
./configure
make
make check
sudo make install
sudo ldconfig
protoc --version

2. GO gRPC
go get -u google.golang.org/grpc
go get -u github.com/golang/protobuf/protoc-gen-go
protoc-gen-go