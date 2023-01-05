# webServer
Linux下基于c++实现的一个轻量级、高性能、高并发的web服务器

## 技术架构
线程池+非阻塞socket+epoll多路复用+并发事件处理+状态机解析http请求+信号捕捉处理+管道通信

## 编译方法
````
g++ *.cpp -lpthread
````

## 启动命令
````
./a.out <port>
````

## 压力测试
在./test_presure/webbench-1.5/下执行：
````
./webbench -c <client_num> -t <time> http://localhost:<port>/index.html
````
