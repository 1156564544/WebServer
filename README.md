# webServer
Linux下c++开发的轻量级、高性能、高并发的web服务器

## 项目中用到的技术架构
线程池+非阻塞socket+epoll多路复用+状态机解析HTTP请求+信号捕捉处理+管道通信

## 编译方法
````
g++ *.cpp <Port>
````
