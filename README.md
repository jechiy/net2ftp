# WordPress

WordPress 是一个功能非常强大的博客系统，插件众多，易于扩充功能，安装和使用都非常方便。目前 WordPress 已经成为主流的 Blog 搭建平台。

## 版本

当前版本 WordPress 4.3.0

## 说明

WordPress 需要搭配 MySQL 数据库才能运行，您可以在启动 WordPress 应用时绑定一个 MySQL 服务来自动完成。

您也可以通过手动设置下面的环境变量来指定 MySQL 连接：

* `MYSQL_DB_HOST`  数据库主机地址（默认为 `MYSQL_PORT_3306_TCP_ADDR`）
* `MYSQL_DB_PORT`  数据库端口（ 默认为 `MYSQL_PORT_3306_TCP_PORT`）
* `MYSQL_INSTANCE_NAME` 数据库名称
* `MYSQL_USERNAME`  数据库用户名
* `MYSQL_PASSWORD`  数据库密码

## 注意

由于上传的文件如图片等会保存在容器中，容器重新部署可能会导致上传文件的丢失，因此不建议您用 WordPress 存储重要文件。


