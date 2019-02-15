# php-docker-image
可以运行PHP的docker镜像

-P使用时需要指定--expose选项，指定需要对外提供服务的端口
docker run -t -P --expose 22 --expose 80 --name server  system

进入容器，开启ssh
docker exec -it <容器ID> /bin/bash

service sshd start

设置root密码
passwd

退出
