2022-07-26

### 打标签
```bash
$ docker tag nginx:latest mynginx:latest
```

### 搜寻镜像
```bash
%% 搜寻官方镜像 %%
$ docker search --filter=is-official nginx
```

### 删除清理镜像
```bash
$ docker rmi mynginx
Untagged: mynginx:latest
$ docker images
REPOSITORY   TAG          IMAGE ID       CREATED        SIZE
nginx        latest       fd2d3e51789e   6 days ago     135MB
```

### 查看所有镜像
```bash
$ docker ps -a
```