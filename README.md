# Samba docker-compose

[中文文档](https://github.com/BlackHole1/samba_docker-ompose/blob/master/README-zh.md)

## Note

1. The default account password is `www`. If you want to change it, Please modify the `docker-compose.yml` eighth line
2. The default mapping directory is `public`. If you want to change it, Please modify the `docker-compose.yml` ten line
3. The default Samba configuration file is `/opt/smb.conf`. If you want to modify it, modify the fifteenth row of `docker-compose.yml` and move the file to the modified directory.
4. Default exposure directory is `/opt/data/`. If you want to change it, Please modify the `docker-compose.yml` sixteen line

## Usage

### Normal start

Enter `docker up -d` at the terminal

### If you use rancher

Enter Add Stack:

![](http://7xppwd.com1.z0.glb.clouddn.com/FlPBfEpxNlyK0WTqSj1166mlKM6q.png)

Copy docker-compose.yml and rancher-compose.yml to rancher:

![](http://7xppwd.com1.z0.glb.clouddn.com/FqxqU5eY3zYWAHdV3KGUaq82g7X_.png)

Click "Cretae" button:

![](http://7xppwd.com1.z0.glb.clouddn.com/FvNLK0j6Z4Lg9H0hRt5tQ5yFgIyb.png)

## Contributing

| **Commits** | **Contributor** | 
| --- | --- |
| 3 | [Black-Hole](https://github.com/BlackHole1) |

## Author

**Black-Hole**

* Email：158blackhole@gmail.com
* Blog：[http://bugs.cc](http://bugs.cc)
* WeiBo：[http://weibo.com/comelove](http://weibo.com/comelove)
* Twitter：[https://twitter.com/Free_BlackHole](https://twitter.com/Free_BlackHole)