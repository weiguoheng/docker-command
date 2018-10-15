# docker-command
docker常用命令

docker ps 						查看正在运行的镜像  
docker images 					来列出本地主机上的镜像  
docker port ID/imageName		来查看容器端口的映射情况。  
docker logs -f ID/imageName		查看容器内部的标准输出。	-f: 让 docker logs 像使用 tail -f 一样来输出容器内部的标准输出。  
docker inspect ID/imageName		查看 Docker 的底层信息记录着 Docker 容器的配置和状态信息  
docker stop ID/imageName		停止 WEB 应用容器  
docker ps -l 					查询最后一次创建的容器  
docker rm ID/imageName			删除不需要的容器  

docker run -t -i ubuntu:15.10 /bin/bash 	使用ubuntu 15.10运行镜像  
docker pull ubuntu:13.10/imageName			下载新的镜像  
docker search imageName						查找镜像  
docker tag 860c279d2fec runoob/centos:dev	860c279d2fec ,用户名称、镜像源名(repository name)和新的标签名(tag)	为镜像添加一个新的标签  
