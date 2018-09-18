# docker-compose-nginx-php
> docker centos7 nginx php rdkafka

### 环境
```php
   系统: centos7
  nginx: 1.13.4
    php: php-7.2.2
php扩展:
    bcmath, Core, ctype, curl, date, dom, fileinfo, filter, gd, gettext, hash, iconv, json, libxml, mbstring, mysqli, mysqlnd, openssl, pcntl, pcre, PDO, pdo_mysql, pdo_sqlite, Phar, posix, rdkafka, Reflection, session, SimpleXML, sockets, SPL, sqlite3, standard, sysvsem, tokenizer, xml, xmlreader, xmlrpc, xmlwriter, xsl, zip, zlib
```


### 使用nginx-php7.2.2-kafka
```sh
cd nginx-php7.2.2-kafka
# 构建、(重新)创建、启动和附加到服务的容器。除非它们已经在运行，否则该命令还会启动任何链接的服务
docker-compose up
# 停止容器并删除容器、网络、卷和图像
docker-compose down
# 查看容器
docker-compose ps
```