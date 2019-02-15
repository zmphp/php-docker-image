# php-docker-image
可以运行PHP的docker镜像

-P使用时需要指定--expose选项，指定需要对外提供服务的端口
docker run -t -P --expose 22 --expose 80 --name server  system
