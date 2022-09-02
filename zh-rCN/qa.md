# 一些常见的问题

## 目录

- [应用权限使用](#应用权限使用)
- [关闭计时通知](#关闭计时通知)
- [与循环计时器有何不同](#与循环计时器有何不同)
- [运行记录不被保存](#运行记录不被保存)
- [iOS版](#ios版)
- [Google Play APK](#google-play-apk)

## 应用权限使用

- 常驻通知、控制振动、防止设备休眠、忽略电池优化、设置闹钟：用于准确计时、按时提醒的功能
- 开机启动：用于在手机重启后，重新设置计划任务以确保其继续运行
- 读写手机储存：用于导出和导入数据文件、选择自定义音乐
- 读取手机状态和身份：**仅用于**在手机来电时，暂停计时器的运行
- 网络：用于提供在线服务和收集应用崩溃信息
- 安装桌面快捷方式：用于创建一键启动计时器的快捷方式
- 显示悬浮窗：用于显示计时悬浮窗

## 关闭计时通知

不可以这么做，但是你可以

1. 你可以在计时器设置页面，点击左边【齿轮】图标，然后关闭这个计时器的【显示计时通知】。这样在运行时，只会有一个显示概览信息的通知。

1. 可以在应用内打开【设置】-【打开通知设置】，在系统设置中关闭特定的通知权限。

## 与循环计时器有何不同

1. 循环计时器已经停止维护，但开发任务并没有停止，计时机器是其继承者/下一代。

2. 在循环计时器中，每个步骤之后的提醒是自动的、全局的，不需要手动添加的。而在计时机器中，需要手动添加一个有行为的步骤，不然是不会得到任何反馈的。

## 运行记录不被保存

在两种情况下应用会保存一次记录：

1. 计时器的最后一个步骤**自然结束**。
1. (应用版本5.2.0及以后) 在计时器的最后一个步骤手动结束。

因此，在计时器的最后一个步骤等待其自然结束，或（在5.2.0版本及以后）手动结束，应用会保存一次记录。

## iOS版

计时机器没有对应的iOS应用，另外出于缺乏时间、能力和设备的原因，现在也没有计划开发iOS版本。

但是这里有一些替代品：

- [Seconds(这个也有Android版)](https://apps.apple.com/cn/app/seconds-%E9%AB%98%E5%BC%BA%E5%BA%A6%E9%97%B4%E6%AD%87%E8%AE%AD%E7%BB%83%E5%AE%9A%E6%97%B6%E5%99%A8/id475816966)
- [Amelia Timer](https://apps.apple.com/cn/app/amelia-timer/id1438196267)
- [PushPress Timer Free](https://apps.apple.com/cn/app/pushpress-timer-free/id826016623)

另外这里有一些关键词，帮你更好的搜索：

- Interval Timer
- HIIT Timer
- Tabata Timer
- Repeating Timer
- Custom Countdown Timer
- 间隔/间歇训练计时器
- 健身计时器
- 自定义计时器

## Google Play APK

如果你从第三方直接下载一个本应用的APK来安装，可能会导致崩溃或无法使用。因此当你不可用或不想用Google Play时，你可以

- [在APK Pure下载应用（需要先安装APK Pure）](https://apkpure.com/timer-machine-run-walk-interval-timer/io.github.deweyreed.timer.google)
- [在这里下载完整版APK手动安装](https://drive.google.com/open?id=1YHIdW77fuxmyQ7sFza1LEIqmhzBygEZx)
