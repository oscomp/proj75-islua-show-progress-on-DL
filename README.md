# proj75-islua-show-progress-on-DL

为iSulad 镜像下载过程添加进度条显示

### *描述* 

当前执行isula pull命令下载镜像时没有任何提示信息，无法知道当前的下载的进度，需要增加下载进度的显示，下载进度显示的打印信息可以参考docker下载镜像时的打印信息。

### *难度* 

难

### *导师* 

@wangfengtu

*联系方式* wangfengtu@huawei.com

### License

- MulanPSL v2



### *项目产出标准*

isula pull下载过程中能显示下载和注册镜像的进度，界面友好(类似docker的界面显示)。

### *技术要求*

- 了解isula/docker的镜像下载过程
- 了解grpc流式服务

### *相关项目*

1. https://gitee.com/openeuler/iSulad

### *相关资料*

- 无具体资料，可以参考docker pull的显示，以及iSulad的pull代码的实现。
