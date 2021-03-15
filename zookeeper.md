## zookeeper note



|  操作  |  命令  |  示例  |  备注  |
|  ---- |  ---  |  ---   |  ---  |
|  macos安装zookeeper  |  1、在命令行中输入brew install zookeeper 2、安装进度100%，完成以后，可以在/usr/local/etc/zookeeper目录下面看到默认的配置文件。 3、启动zookeeper,在命令行中执行命令zkServer start来启动zookeeper。 |
|  连接zookeeper | zkCli |
|  查询zookeeper版本 ｜ 连接到zookeeper后输入命令：version |
|  查询zookeeper下已注册的服务 | ls /services/ |
|  查询指定服务的hash值 | ls /services/服务名称 |
|  根据服务的hash值查询服务详情| get /services/服务名称/服务hash值  |
