# mjpeg
本地mjpeg推流到服务端
#### 自动下载包
#### go mod tidy

#### 启动服务端
#### go run server.go


#### 启动客户端
#### go run client.go 0 0.0.0.0:8080


### 查看效果
http://127.0.0.1:12312/sp

客户端可打开摄像头 并向服务端发送websocket数据前提是你开启了服务端

服务端接收客户端数据并提供可以观看的http服务
