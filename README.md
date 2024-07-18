# chatserver
本项目提供了一个可以在 Nginx TCP 负载均衡环境中运行的集群聊天服务器和客户端源码。该项目基于 Muduo 网络库实现，具备高并发处理能力和良好的扩展性，适用于大规模分布式聊天系统的开发。

## 1.编译
```shell
cd build
cmake ..
make
```
## 2.服务端
```shell
cd bin
./ChatServer 127.0.0.1 6000
./ChatServer 127.0.0.1 6002
```
## 3.客户端
```shell
cd bin
./ChatClient 127.0.0.1 8000
```
