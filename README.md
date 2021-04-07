# ngrok1.7 使用指南


**ngrok是一个反向代理，它能够让你本地的web服务或tcp服务通过公共的端口和外部建立一个安全的通道，使得外网可以访问本地的计算机服务。**
**

- **支持https访问**
- **固定域名**
- **替代花生壳**
- **TCP 端口转发**


### 使用方法
> 1. 下载对应的客户端
> 1. 修改配置文件
> 1. 运行


下载对应的客户端
```
Linux 平台 32 位系统：linux_386
Linux 平台 64 位系统：linux_amd64
Windows 平台 32 位系统：windows_386 
Windows 平台 64 位系统：windows_amd64  
MAC 平台 32 位系统：darwin_386 
MAC 平台 64 位系统：darwin_amd64 
ARM 平台：linux_arm
```


#### 方法一
下载客户端，在客户端运行
```
.\ngrok -config ngrok.yml start demo
```
#### 方法二
新建文件 改名 `start.bat`
输入：
```
ngrok -config=ngrok.cfg start xxx
```
直接双击运行

#### 方法三
添加全局变量，或者移动文件：百度一下


### 运行报错
启动失败的话，加一下log文件看一下问题
```javascript
.\ngrok -config ngrok.yml -log log.txt start demo
```
解决不了的话留言哈
=======
# ngrok1.7 使用指南


**ngrok是一个反向代理，它能够让你本地的web服务或tcp服务通过公共的端口和外部建立一个安全的通道，使得外网可以访问本地的计算机服务。**
**

- **支持https访问**
- **固定域名**
- **替代花生壳**
- **TCP 端口转发**


### 使用方法
> 1. 下载对应的客户端
> 1. 修改配置文件
> 1. 运行


下载对应的客户端
```
Linux 平台 32 位系统：linux_386
Linux 平台 64 位系统：linux_amd64
Windows 平台 32 位系统：windows_386 
Windows 平台 64 位系统：windows_amd64  
MAC 平台 32 位系统：darwin_386 
MAC 平台 64 位系统：darwin_amd64 
ARM 平台：linux_arm
```


#### 方法一
下载客户端，在客户端运行
```
.\ngrok -config ngrok.yml start demo
```
#### 方法二
新建文件 改名 `start.bat`
输入：
```
ngrok -config=ngrok.cfg start xxx
```
直接双击运行

#### 方法三
添加全局变量，或者移动文件：百度一下


### 运行报错
启动失败的话，加一下log文件看一下问题
```javascript

.\ngrok -config ngrok.yml -log log.txt start demo
```
解决不了的话留言哈

