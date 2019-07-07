# docker-demo

使用build命令构造镜像,注意后面那个.不能少。

docker build -t docker_demo .

#启动镜像 -d表示后台执行，-p 9000:3000表示指定本地的9000端口隐射到容器内的3000端口，docker_demo为镜像名称

docker run -d -p 9000:3000 docker_demo

#查看容器

docker ps
