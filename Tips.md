1. 查看占用8080端口号的进程PID
   netstat -ano | findstr 8080

2. mysql：
   登录：mysql -uroot -p1234

   启动：net start mysql

3. redis：

   启动：redis-server.exe redis.windows.conf

   退出：ctrl+c
   
   默认端口号：6379
   
   配置密码：redis.windows.conf  -> requirepass 123456
   
   连接到客户端：redis-cli.exe -h localhost -p 6379 -a 123456
   
   关闭客户端：exit
   
   4.nacos
   
   单例模式启动：startup.cmd -m standalone