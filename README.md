# Weaviate-install-window11

该文将讲述如何Window11中本地部署Weaviate(使用Docker)。

一共有两种方案，一是官网文档中下载方式，另外一种是下载GitHub上的。
# 官网方法
进入该[网址](https://weaviate.io/developers/weaviate/installation/docker-compose)，自定义安装(自己选择安装什么模块)

之后，复制自己的安装命令，在想要安装的文件夹中输入cmd，打开命令行，命令行中输入该安装命令。

![af82da5372c9611f17152c941306caed507f519d93ff806aa6f6e30da8d8b63fQzpcVXNlcnNcQWRtaW5pc3RyYXRvclxBcHBEYXRhXFJvYW1pbmdcRGluZ1RhbGtcMTQ2NTk4OTcxN192MlxJbWFnZUZpbGVzXDE2ODkyMTE5NzA0NzlfQkU2OEQyOTAtRjc3RC00ZWVlLUExQTQtNzNCODQxNTk3MkIzLnBuZw==](https://github.com/LuJH12/Weaviate-install-window11/assets/78155731/0902fd86-ee8e-4847-a6a2-57ec9e46ca49)


在下载完成后，输入下述命令，在后台启动容器并使它们运行。

`docker-compose up -d`

这样，就已经成功将Weaviate本地部署，可以进入`http://localhost:8080/`检验是否成功。

# GitHub下载方法
注意！！！！这种方法需要安装的时间较长，需要下载20G+。方法进入官网的[GitHub地址](https://github.com/weaviate/weaviate)，下载其中的`docker-compose.yml`文件，存放在你想安装镜像的文件夹中
![5c9de1ddb45568adfd60a96b731d61fc367d7576ba0af8a8b7204284264cdcbbQzpcVXNlcnNcQWRtaW5pc3RyYXRvclxBcHBEYXRhXFJvYW1pbmdcRGluZ1RhbGtcMTQ2NTk4OTcxN192MlxJbWFnZUZpbGVzXDE2ODkyMTIwMzM4NDJfOERBMUNENjAtRDY3RC00YzlmLTg2NjUtMjZCNEI2QUY0RjdGLnBuZw==](https://github.com/LuJH12/Weaviate-install-window11/assets/78155731/9d0c1bfc-cfe0-44ef-a293-ef892f23e551)

然后在该文件夹中进行命令行窗口，输入

`docker-compose up -d`

即可开始下载Weaviate及其他模块。


未完，待补充。。。
