# chatserver
集群聊天服务器和客户端代码  基于muduo库实现  工作在nginx tcp负载均衡环境中  redis发布与订阅的实践

编译方式：  
cd build  
rm -rf *  
cmake ..  
make

技术栈：  
muduo网络库开发  
json序列化和反序列化  
配置nginx基于tcp的负载均衡  
基于redis发布-订阅功能  
使用mysql关系型数据库
