# 串口wifi模块

![](https://raw.githubusercontent.com/fly-t/images/main/blog/README-2024-09-03-22-10-20.png)


# 文件目录

1. 串口工具太难用, 直接使用串口助手发命令 (串口也有毛病, 搞笑的一批)
2. 软件名字不能修改

![](https://raw.githubusercontent.com/fly-t/images/main/blog/README-2024-09-03-18-21-21.png)


# 1. 开启文件服务器

开启文件上传服务器`HFUpdate.exe`

![](https://raw.githubusercontent.com/fly-t/images/main/blog/README-2024-09-03-18-23-11.png)

![](https://raw.githubusercontent.com/fly-t/images/main/blog/README-2024-09-03-18-23-38.png)

![](https://raw.githubusercontent.com/fly-t/images/main/blog/README-2024-09-03-18-23-47.png)


# 1.5 修改配置

修改 `LPB100通用版本WIFI升级_V1_XJ.dat`, 主要是修改wifi ssid 和密码. 让模块接入.

![](https://raw.githubusercontent.com/fly-t/images/main/blog/README-2024-09-03-18-26-12.png)



# 2. 打开 'serial_tools.exe'

选择对应配置

![](https://raw.githubusercontent.com/fly-t/images/main/blog/README-2024-09-03-18-24-49.png)

会提示失败

![](https://raw.githubusercontent.com/fly-t/images/main/blog/README-2024-09-03-18-28-30.png)

失败没事, 我们手动发送即可

![](https://raw.githubusercontent.com/fly-t/images/main/blog/README-2024-09-03-18-28-22.png)


# 激活串口的方法!!!!!!

第一次上电发送啥AT指令都不好使.

使用串口发送"+++"不带换行!!!. 发送两次有一定间隔发送.串口回复a就表示可以使用了. 傻x行为


![](https://raw.githubusercontent.com/fly-t/images/main/blog/README-2024-09-03-18-32-12.png)