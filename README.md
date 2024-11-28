## 树莓派的系统和环境

1. [树莓派系统安装](#树莓派系统安装)
2. [SSH连接](#ssh连接)

### 树莓派系统安装

安装工具(Raspberry Pi Imager)
[Download for Windows](https://downloads.raspberrypi.org/imager/imager_latest.exe)
[Download for macOS](https://downloads.raspberrypi.org/imager/imager_latest.dmg)
[Download for Ubuntu for x86](https://downloads.raspberrypi.org/imager/imager_latest_amd64.deb)

按自己的电脑系统选



**选择板子类型, 根据自己板子选**

​	我的是树莓派5(8G的可以玩mod了，真好！)



**选择操作系统**

​	选择 ---> Other general-purpose OS ---> ubuntu24.10 

![image-20241128181109009](/Users/x_lin/Library/Application Support/typora-user-images/image-20241128181109009.png)



**格式化SD卡**

​	**一定要选择自己的读卡器读出来的SD卡!!!!!!**

![截屏2024-11-28 18.04.05](/Users/x_lin/Downloads/录制视频/截屏2024-11-28 18.04.05.png)



**网络配置和ssh配置**

点击NEXT, 编辑设置

`GENERAL` 系统设置

```text
主机名: Lin		(举个🌰)

用户名: Lin		(举个🌰)

密    码: zhanglin       (举个🌰)

热点名称: Lin (按实际情况)
	这个说明一下, 如果是用的是手机热点, 现在都是有IPv6的，这个可以省掉一笔代理的费用。如果是Wi-Fi的话，我目前没弄IPv6的IP。

密	码: zhanglin(按实际情况)

Wi-Fi国家: CN

时区选择国内的就行
```



`SERVICES` 设置

```
开启ssh服务
使用密码登陆
```



点击 `保存`，点击 `是`， 等待烧录完成。

![image-20241128182829543](/Users/x_lin/Library/Application Support/typora-user-images/image-20241128182829543.png)



Ok啊，到这里算是完成了一小半了。记得弹出SD卡。

然后SD插入树莓派，开机。等待系统安装，大概需要半个小时到时间。



## SSH连接
