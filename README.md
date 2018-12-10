# 安装ansible
yum install -y ansible
# 查看安装版本，请到每个files里面查看

# 使用该剧本

在site加上role即可，然后执行 ansiple-playbook site.yml  此处site.yml可以使用绝对路径

# 注意：

ICE：安装有问题，安装javaICE的时候，需要去网上下载,npm 也会去网上下载。可以使用npm本地包

zabbix，elk，使用的是rpm安装

for i in `ls * -d`;do mkdir -p $i/files;done

# 下载文件地址

下载文件请到官网 or 公开源下载， 例如清华源，阿里云源等

```sh

nginx： wget http://nginx.org/download/nginx-1.14.2.tar.gz


php： wget http://cn2.php.net/distributions/php-7.2.13.tar.gz

1. wget https://github.com/phpredis/phpredis/archive/4.1.1.tar.gz

2. wget https://github.com/swoole/swoole-src/archive/v4.2.9.tar.gz

3. wget https://services.gradle.org/distributions/gradle-4.7-bin.zip


mysql： wget https://mirrors.tuna.tsinghua.edu.cn/mysql/downloads/MySQL-5.7/mysql-5.7.24.tar.gz

tomcat： wget https://mirrors.tuna.tsinghua.edu.cn/apache/tomcat/tomcat-8/v8.5.35/bin/apache-tomcat-8.5.35.tar.gz


elk：

1. wget https://artifacts.elastic.co/downloads/logstash/logstash-6.5.2.rpm

2. wget https://artifacts.elastic.co/downloads/elasticsearch/elasticsearch-6.5.2.rpm

3. wget https://artifacts.elastic.co/downloads/kibana/kibana-6.5.2-x86_64.rpm


nodejs： wget https://mirrors.tuna.tsinghua.edu.cn/nodejs-release/v8.11.4/node-v8.11.4.tar.gz

redis: wget http://download.redis.io/releases/redis-5.0.2.tar.gz 

python3: wget https://www.python.org/ftp/python/3.7.1/Python-3.7.1.tgz

ice:  wget https://github.com/zeroc-ice/ice/archive/v3.7.1.tar.gz

1. wget https://codeload.github.com/zeroc-ice/mcpp/tar.gz/v2.7.2.13

```
