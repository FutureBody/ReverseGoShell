## ReverseGoShell

Windows:[Releases](https://github.com/TheKingOfDuck/ReverseGoShell/releases/download/1.0/ReverseGoShell.zip)

# Update log：

2020-03-16：
  新增一个macOS版本的客户端，理论上Linux都可以的，最多改下命令解释的二进制就好了。


### Description:

A Golang Reverse Shell Tool With AES Dynamic Encryption

```
 _____                               _____       _____ _          _ _ 
|  __ \     Code By: CoolCat       / ____|     / ____| |        | | |
| |__) |_____   _____ _ __ ___  ___| |  __  ___| (___ | |__   ___| | |
|  _  // _ \ \ / / _ \ '__/ __|/ _ \ | |_ |/ _ \\___ \| '_ \ / _ \ | |
| | \ \  __/\ V /  __/ |  \__ \  __/ |__| | (_) |___) | | | |  __/ | |
|_|  \_\___| \_/ \___|_|  |___/\___|\_____|\___/_____/|_| |_|\___|_|_| 
 - | Modules    | - Function.
 - | checkav    | - Show Remote-Host Info.
 - | Download   | - Download File from Remote-Host to Local-Host.
 - | Keyloger   | - Unfinished.
 - | Screenshot | - Unfinished.

```

### Useage:

#### Build

```
go build server.go
go build client.go
```
![build](https://github.com/TheKingOfDuck/ReverseGoShell/blob/master/images/build.jpg)

#### Run

```
server 55555
client 127.0.0.1:55555
```

![](https://github.com/TheKingOfDuck/ReverseGoShell/blob/master/images/run.jpg)


### Features

* AES Dynamic encryption
* Supports Multiple Shells

### About

这个项目只是自己学习Golang过程中实践的产物，代码写得很垃圾，但是注释都尽量写清楚的，通讯流量走tcp协议，采用aes动态加密，可以说是完全模仿冰蝎。基础功能执行命令已实现，模块化的检查存在的杀毒软件以及下载文件写完，其他模块还得在花时间。相比同类小工具我觉得最大的优点就是支持了动态加密，并且可以同时管理多个会话。

**本项目接受建议**

比如希望增加特定功能，再比如某个位置代码写得不规范，或是有bug，有空我会慢慢改。
