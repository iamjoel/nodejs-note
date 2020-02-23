# linux
## 创建目录
直接创建多级目录，用 `-p` 参数
```
mkdir -p a/b/c
```

## 后台运行
`命令 &`

## 后台挂起
远程服务器，退出后，也不杀死进程
`nohup 命令 &`

## 杀死进程
查看进程 `ps -ef`  
更加进程id 杀死进程 `kill pid`

因为 nohup 命令需要片刻时间来启动 Command 参数指定的命令，在注销前请等待。如果太快注销，Command 参数指定的命令可能根本没运行。一旦 Command 参数指定的命令启动，注销就不会对其产生影响。

## 用管理员的方式运行命令
sudo