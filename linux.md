## linux note



|  操作  |  命令  |  示例  |  备注  |
|  ---- |  ---  |  ---   |  ---  |
|  安装svn  |  yum install subversion  |
|  svn下载版本库  |  svn checkout  http://203.171.231.17:8199/svn/sanzi_suzhou  |
|  linux 执行sh文件权限不够  |  chmod  a+x  文件名  |
|  查询进程  |  ps -ef \|grep 进程名 |  ps -ef \|grep redis |
|  linux 安装redis  |    |   |  参考网址：https://www.cnblogs.com/hunanzp/p/12304622.html  |
|  停止redis  |  ./bin/redis-cli shutdown  |
|  使用配置文件启动redis  |  ./bin/redis-server /usr/local/redis/etc/redis.conf  |
|  解压zip  |  unzip filename.zip  |
|  查看防火墙已经开放的端口  |  firewall-cmd --list-ports  |
|  开放防火墙的指定端口  |  firewall-cmd --zone=public --add-port=80/tcp --permanent  |
|  重启防火墙  |  systemctl reload firewalld  |
|  复制文件夹  |  cp -r dir1 dir2  |
|  强制杀死进程 |  kill -9 pid  |

