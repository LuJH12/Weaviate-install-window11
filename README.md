# Weaviate-install-window11

该文将讲述如何Window11中本地部署Weaviate(使用Docker)。

一共有两种方案，一是官网文档中下载方式，另外一种是下载GitHub上的。
# 官网方法
进入该[网址](https://weaviate.io/developers/weaviate/installation/docker-compose)，自定义安装(自己选择安装什么模块)

之后，复制自己的安装命令，在想要安装的文件夹中输入cmd，打开命令行，命令行中输入该安装命令。
![e7b5d6d43c9c184c8f74cf801291add](https://github.com/LuJH12/Weaviate-install-window11/assets/78155731/432bc498-f7bd-4897-9896-b343fa17a7c3)

在下载完成后，输入下述命令，在后台启动容器并使它们运行。

`docker-compose up -d`

这样，就已经成功将Weaviate本地部署，可以进入`http://localhost:8080/`检验是否成功。

# GitHub下载方法
进入官网的[GitHub地址](https://github.com/weaviate/weaviate)，下载其中的`docker-compose.yml`文件，存放在你想安装镜像的文件夹中
![1688452893457](https://github.com/LuJH12/Weaviate-install-window11/assets/78155731/f24b6376-627e-42ee-973f-14f1b1705f6a)

然后在该文件夹中进行命令行窗口，输入

`docker-compose up -d`

即可开始下载Weaviate及其他模块。


未完，待补充。。。
