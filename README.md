English version of the README -> please [click here](./README-EN.md)

# 先读我

## 1. 运行 Demo 需以下步骤
1. 电脑可用网线连接控制器的网口，然后设置固定 IP，与控制器 IP 在同一网段下。也可无线连接控制器。

   - 四轴机器人（如MG400等）     有线连接时连接LAN1：ip为192.168.1.6 , 有线连接时连接LAN2：ip为192.168.2.6,  无线连接：ip为192.168.9.1
   - 六轴机器人（如CR系列等）    有线连接：ip为192.168.5.1 , 无线连接：ip为192.168.1.6
  
2. 尝试 ping 通控制器 IP，确保在同一网段下。

## 2. 文件说明
1. demo.py: 程序运行入口。  
   
2. dobot_api.py：根据机器人TCP/IP远程控制方案（https://github.com/Dobot-Arm/TCP-IP-Protocol）自行修改。

## 3. 运行Demo
方法一: 需要检测搜索到动态库，需在**VsCode**中打开整个目录，再直接运行 demo.py。  

方法二: 需要检测搜索到动态库，需在**PyCharm**中打开整个目录，再直接运行 demo.py。

## 4. 测试环境
- language: Python 3.7 64-bit
- os: Windows 10 64-bit

## 5.控制器版本
可以使用TCP/IP协议的控制器版本如下：  

- MG400： 1.5.4.0 及以上
- CR： 3.5.1.9 及以上

