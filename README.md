# proj69-isula-build-run

实现在容器中运行isula-build

### *描述*  

目前isula-build 的启动方式是在主机侧启动systemd服务，或手动启动服务进程。理论上isula-build支持在容器内运行，需要进行验证并提供Dockerfile

### *难度*  

易

### *导师*  

@jingxiaolu

*联系方式*  lujingxiao@huawei.com

### License

- MulanPSL v2

### *项目产出标准*

- 制作能够运行isula-build的容器镜像，并推送到远端镜像仓库
- 使用 iSulad 能够使用下载后的镜像，以容器形式启动运行，基本功能可用

### *技术要求*

1. Dockerfile 语法
2. Docker 制作镜像，推送镜像等基本操作

### *相关项目*

1. https://gitee.com/openeuler/isula-build

### *相关资料*

1. https://docs.docker.com/engine/reference/commandline/build/
