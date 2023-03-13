#### Redis常用命令

##### 1、需要使用的命令

redis-server.exe redis.windows.conf   //开启服务
redis-cli.exe  //开启客户端
redis-server --service-install redis.windows.conf --loglevel verbose  //注册服务

##### 2、常用的命令

redis-server --service-uninstall    //卸载服务
redis-server --service-start     //开启服务
redis-server --service-stop      //停止服务
