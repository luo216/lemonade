# 本地操作

```shell
从 https://github.com/lemonade-command/lemonade/releases 下载自己可用的lemonade版本
例如我是linux直接下载 lemonade_linux_386.tar.gz 包

gzip -d lemonade_linux_386.tar.gz
tar -xvf lemonade_linux_386.tar.gz

得到 lemonada 可执行文件
本地启动 lemonada 可执行文件服务端

./lemonada server
```

# 远程操作

```shell
同理 下载对应系统的lemonada 可执行文件 放置在 /usr/bin 目录下即可
```

# 本地访问远程ssh,并转发端口

```shell
ssh -R 2489:127.0.0.1:2489 user@host

然后就可以享受两端同步的剪切板了
```
