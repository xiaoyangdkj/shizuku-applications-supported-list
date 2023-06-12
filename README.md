# shizuku-applications-supported-list-wiki
Shizuku使用教程（从小白到小白）

[![shizuku-logo]](https://shizuku.rikka.app/)

--------------------


## 使用教程

- [准备工作](#准备工作)
  - [MIUI小米.红米](#MIUI小米红米)
  - [ColorOS一加.OPPO](#ColorOS一加OPPO)
  - [Huawei华为](#Huawei华为)
- [启动Shizuku](#启动Shizuku)
  - [通过 root 启动](#通过root启动)
  - [通过无线调试启动](#通过无线调试启动)
  - [通过连接电脑启动](#通过连接电脑启动)
- [启动后能干什么呢](#启动后能干什么呢)
- [常见问题](#常见问题)
--------------------

## 准备工作


### MIUI小米红米
1.设置-我的设备-全部参数-找到“miui版本”并连续点击五次
[![miui-device]](https://www.coolapk.com/feed/45300089)

2.设置-系统管理-开发者选项
[![miui-adb-turn-on]](https://www.coolapk.com/feed/45300089)
找到“USB 调试”,“USB 安装”,“USB 调试（安全设置）”,“停用 adb 授权超时功能”选项，将它们一起打开

### ColorOS一加OPPO
1.设置-关于本机-找到“版本号”并连续点击几次
[![coloros-device]](https://www.coolapk.com/feed/46509870)

2.设置-其他设置-开发者模式
[![coloros-adb-turn-on]](https://www.coolapk.com/feed/40627917)
找到“USB 调试”,“禁止权限监控”,“停用 adb 授权超时功能”选项，将它们一起打开

### Huawei华为
1.设置-关于手机-找到“版本号”并连续点击几次
[![huawei-device]](https://www.coolapk.com/feed/46509870)

2.设置-其他设置-开发者模式
[![huawei-adb-turn-on]](https://www.coolapk.com/feed/40627917)
找到“USB 调试”,“仅充电模式下允许 ADB 调试”选项，将它们一起打开

--------------------

## 启动Shizuku


### 通过root启动
在Shizuku内“启动”-授权

### 通过无线调试启动
在Shizuku内“启动无线调试”
[![shizuku-wireless-debugging-start-example]](https://www.coolapk.com/feed/45300089)

回到“开发者选项”-查找“无线调试”并开始配对
[![miui-wireless-debugging-example]](https://www.coolapk.com/feed/45300089)

在下滑通知栏中输入配对码，完成配对启动
[![miui-wireless-debugging-finish-example]](https://www.coolapk.com/feed/45300089)

### 通过连接电脑启动
这里有两种启动方法

一.手机连接电脑，浏览器打开[Adb在线执行器](https://adb.http.gs/ "Adb在线执行器")，在确定好“激活模式”和“USB调试已打开”后选择“点击激活Shizuku”

二.电脑上下载“搞机工具箱”，在确认好“USB调试已打开”后切换到“ADB指令”界面，复制粘贴执行

adb shell sh /storage/emulated/0/Android/data/moe.shizuku.privileged.api/start.sh

--------------------

## 启动后能干什么呢

示例：使用支持Shizuku的“爱玩机工具箱”破除安装时需要密码验证的问题
![][huawei-pure-example]
![][huawei-impure-start-example]
![][huawei-impure-finish-example]

--------------------

### 常见问题
详细请看:https://shizuku.rikka.app/zh-hans/guide/setup/


[shizuku-logo]:/image/Shizuku-logo.png "shizuku-logo"
[miui-device]:/image/miui-device.jpg "miui打开开发者选项"
[miui-adb-turn-on]:/image/miui-adb-turn-on.jpg "miui打开usb调试"
[coloros-device]:/image/coloros-device.jpeg "coloros打开开发者模式"
[coloros-adb-turn-on]:/image/coloros-adb-turn-on.jpg "coloros打开usb调试"
[huawei-device]:/image/huawei-device.jpg "华为设备打开开发者模式"
[huawei-adb-turn-on]:/image/huawei-adb-turn-on.jpg "华为设备打开usb调试"
[shizuku-wireless-debugging-start-example]:/image/shizuku-wireless-debugging-start-example.jpeg "shizuku开始无线调试"
[miui-wireless-debugging-example]:/image/miui-wireless-debugging-example.jpeg "shizuku开始无线调试"
[miui-wireless-debugging-finish-example]:/image/miui-wireless-debugging-finish-example.jpeg "shizuku开始无线调试"
[huawei-pure-example]:/image/huawei-pure-example.jpg "华为纯净模式被关闭前"
[huawei-impure-start-example]:/image/huawei-impure-start-example.jpg "爱玩机工具箱"
[huawei-impure-finish-example]:/image/huawei-impure-finish-example.jpg "华为纯净模式被关闭后"