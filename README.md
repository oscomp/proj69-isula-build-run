# proj69-isula-build-run

实现在容器中运行isula-build

### *描述*  

目前isula-build 的启动方式是在主机侧启动systemd服务，或手动启动服务进程。理论上isula-build支持在容器内运行，需要进行验证并提供Dockerfile

### 所属赛道

2021全国大学生操作系统比赛的“OS功能设计”赛道



### 参赛要求

- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生（2021年春季学期或之后本科毕业的大一~大四的学生）
- 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
- 请遵循“2021全国大学生操作系统比赛”的章程和技术方案要求

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
