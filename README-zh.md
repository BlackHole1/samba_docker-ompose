# Samba docker-compose

[English document](https://github.com/BlackHole1/samba_docker-ompose/blob/master/README.md)

## Note

1. 默认的账号密码是`www`，如果你想修改它，请修改`docker-compose.yml`的第8行
2. 默认的映射目录是`public`，如果你想修改它，请修改`docker-compose.yml`的第10行
4. 默认的samba配置文件是`/opt/smb.conf`，如果你想修改它，请修改`docker-compose.yml`的第15行, 并将此文件移到修改后的目录下
3. 默认的暴露目录是`/opt/data/`，如果你想修改它，请修改`docker-compose.yml`的第16行

## Usage

### 正常启动

在终端输入`docker up -d`

### 如果你使用的是rancher

进行添加应用:

![](http://7xppwd.com1.z0.glb.clouddn.com/FlPBfEpxNlyK0WTqSj1166mlKM6q.png)

复制`docker-compose.yml`和`rancher-compose.yml`到`rancher`里:

![](http://7xppwd.com1.z0.glb.clouddn.com/FqxqU5eY3zYWAHdV3KGUaq82g7X_.png)

点击 "创建" 按钮:

![](http://7xppwd.com1.z0.glb.clouddn.com/FvNLK0j6Z4Lg9H0hRt5tQ5yFgIyb.png)