## consul note



|  操作  |  命令  |  示例  |  备注  |
|  ---- |  ---  |  ---   |  ---  |
|  macos安装consul  |  1、官网下载（https://www.consul.io/downloads.html）macos consul。 2、下载解压后，将文件放置在 /usr/local/bin 目录下。 3、检测安装情况：并查看版本：consul --version|
|  启动consul| consul agent -dev |

### 注意
1、Consul的服务节点是临时节点，一定时间内收不到注册服务的“心跳”就会删除该注册服务。
2、Consul默认端口号是：8500

