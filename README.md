# Leaning-spring-cloud-YangZhou-config
 学习Spring Cloud所用Config仓库

#### 手动刷新方式：
每次提交完commit之后，需要向spring-config-client端发送一个POST请求方可。
若端口为3355，则发送: curl -X POST "http://hostname:3355/actuator/refresh"
其中，hostname为主机名，若为本机，则为localhost
