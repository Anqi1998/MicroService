# MicroService
安装micro插件
1.安装protoc-gen-go
下载压缩包protoc-gen.zip解压到$GOPATH/src/github.com/golang/protobuf
在终端运行go build生成可执行文件protoc-gen-go
最后执行sudo cp protoc-gen-go /bin  即可



2.安装protoc-gen-micro
下载压缩包protoc-gen.zip解压到$GOPATH/pkg/mod/github.com/micro
在终端运行go build生成可执行文件protoc-gen-micro
最后执行sudo cp protoc-gen-micro /bin  即可
