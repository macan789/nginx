# nginx

#2015-08-16

#
cd /root
docker build -t "evada/ubuntu:v1.0" .

#创建容器
docker run -it -d -p 10280:80 evada/ubuntu:v1.0 /bin/bash

#启动nginx服务
/usr/sbin/nginx -c /etc/nginx/nginx.conf

#测试访问
http://192.168.230.4:10280/
