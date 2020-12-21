## mysql note



|  操作  |  命令  |  示例  |  备注  |
|  ---- |  ---  |  ---   |  ---  |
|  连接数据库  |  mysql -h192.168.5.14 -u szuser -p  |
|  查询当前连接下的所有数据库  |  show databases;  |
|  选取数据库  | use 数据库名称;  |
|  退出mysql控制台  |  使用ctrl+c快捷键，或者exit命令 |
|  查询mysql版本  ｜ select version(); |
|  创建数据库，并指定编码和排序｜ create database dbname default character set utf8 collate utf8_general_ci; ｜
|  删除表 ｜ drop table 表名 ｜

### mysql创建表

create table user(id int unsigned auto_increment, username varchar(30) not null, password varchar(50) not null, primary key (id));

