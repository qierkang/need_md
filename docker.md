docker search 查询docker仓库
(去 docker hub 搜索)

docker pull (镜像名)
下载最新的镜像
docker pull (镜像名):tag
下载指定版本


docker images
查看docker下载镜像

docker rmi (镜像id)
删除docker镜像

docker运行容器
docker run --name (自己取名字) -d (后台运行) (镜像名字:tag)


docker查看运行中容器
docker ps

docker容器停止
docker stop (容器id)

docker容器启动
docker start (容器id)

docker容器删除
docker rm (容器id)

docker端口映射

 docker run -d -p 8080:8080 tomcat
-p表示端口映射 主机端口映射容器内部端口

servie firewalld status 查看防火墙
service firewalld stop 临时关闭防火墙

docker容器日志
docker logs (容器名或者容器id)

docker命令参考
https://docs.docker.com/engine/reference/commandline/docker/

docer操作流程
1.下载软件镜像
2.运行镜像
3.产生一个容器
