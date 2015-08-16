# nginx

#创建容器
docker run -it -d -p <宿主机端口>:80 evada/nginx:v1.0 /bin/bash

#启动nginx服务
/usr/sbin/nginx -c /etc/nginx/nginx.conf

#测试访问
http://<宿主机IP>:<宿主机端口>/
