# FuckJfglzs
Fuck the malware jfglzs. / 清除恶意软件「学生机房管理助手」。

# 温馨提示 / Tips
本项目正在开发中（暂时没有进度（懒））

# What is jfglzs? / 什么是「学生机房管理助手」？
「学生机房管理助手」是一个行为恶劣的恶意软件。

## jfglzs behaviors / 「学生机房管理助手」的行为
- 禁用系统管理工具 （任务管理器、注册表编辑器、命令提示符、组策略编辑器...）
- 禁用或阻止访问系统功能（如「运行」、注销、切换用户、移除Ctrl-Alt-Delete界面的选项）
- 禁用一些Windows功能，包括但不限于：扫雷、蜘蛛纸牌
- 禁用部分浏览器功能，如：chrome://dino、edge://surf
- 进行映像劫持（IFEO），如：添加[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\taskkill.exe] "debugger"="null" 防止运行taskkill工具
- 全面防止计算机脱离万恶的「电子教室」的控制
- 阻止访问USB存储设备
- 蓝屏锁机
- 创建一堆进程、放在随机目录中，互相守护，防止检测
- 自动从互联网下载安装此恶意软件的新版本
- **篡改并锁定浏览器主页为该恶意软件作者的2345推广页**
- 等等...

## 「学生机房管理助手」常见地点
- 学校机房

## 「学生机房管理助手」测试地点

<div style="font-size: x-large; color: red; font-weight: bold;">IMPORTANT: 重要警告！！</div>

「学生机房管理助手」是一个**恶意软件**并且会**篡改系统设置**，即使卸载也存在**无法还原到之前状态**的情况。如果您要测试此恶意软件，请确保**在虚拟机中**进行。由于测试此软件对个人电脑造成任何损失的，**此repo的作者不承担任何责任**！！！

jfglzs is a **malware** that can **tamper with system settings**, and even if uninstalled, there may be situations where it **CANNOT be restored to its previous state**. If you want to test this malware, please **ensure it is done in the virtual machine**. **The author of this repo will not be held responsible for any losses caused to personal computers due to testing this malware**!!!

要下载「学生机房管理助手」，请前往 [http://www.jfglzs.com/](http://www.jfglzs.com/) / To download jfglzs, go to [http://www.jfglzs.com/](http://www.jfglzs.com/)

# FuckJfglzs features / 「FuckJfglzs」功能

- 结束所有「学生机房管理助手」相关进程，防止蓝屏锁机
- （可选）恢复被「学生机房管理助手」篡改的系统设置
- （可选）恢复被「学生机房管理助手」禁用的系统组件
- （可选）爆破「学生机房管理助手」，尝试从计算机上移除此恶意软件

# How to use / 如何使用

## 重要提示
1. 在开始下列操作前，请先尽量关闭其他程序，防止被误伤

## 情况1：可以使用U盘
1. 提前在releases里面下载好本程序（要确保位数对应，64位系统只能用64位程序，32位的可能无法正常工作）
2. 复制到U盘中，并把文件名改乱（改掉默认文件名，不要使用默认文件名，否则会被检测，这一步非常重要，只要随便改名就行了，例如gyehjnv34t5j.exe，或winword.exe之类看似正常的名字也行）
3. 把U盘插到目标计算机上，把本程序复制出来
4. 打开本程序，不出意外的话不会触发检测，然后按照提示操作即可。
## 情况2：U盘使用被限制
1. 在目标计算机中，通过网络在releases里面下载好本程序（要确保位数对应，64位系统只能用64位程序，32位的可能无法正常工作）；下载重要事项：**一定**在下载时把文件名改乱（参考情况1的改名），chrome浏览器需要提前在设置中打开“下载前询问每个文件的保存位置”然后下载时自定义文件名，360之类的浏览器可以直接在下载时自定义文件名
2. 打开本程序，不出意外的话不会触发检测，然后按照提示操作即可。

# FAQ / 常见问题

## Q: 打开程序时被蓝屏锁机了，怎么办？
**A**：正常情况下，本程序打开后会自动结束「学生机房管理助手」，所以几秒后蓝屏窗口就会自动消失；如果没有消失，请参照改名部分，把文件名稍微改正常一点（例如“WinWord.exe”，“WeChat.exe”等）然后再次尝试；如果改了后仍旧被蓝屏，请开一个issue，最好附上系统版本和「学生机房管理助手」的版本。

## Q: 关掉「学生机房管理助手」后，要如何解决电子教室？
**A**：对于「极域电子教室」，强烈推荐[JiYuTrainer项目](https://github.com/imengyu/JiYuTrainer)，功能十分强大；对于其他电子教室，可以先试一下通用的方法。另外，**去GitHub上搜索“极域”、“电子教室”、“机房”等关键词有惊喜。**

## 其他问题
请去开一个issue，最好附上系统版本和「学生机房管理助手」的版本。

# License / 许可证

本repo采用 *GNU General Public License version 3* (GPL 3)许可证。这意味着，本repo中的**所有内容**是**自由**的。并且，作者表示，**任何**此程序的源码、二进制文件等都是**免费**提供的，所有源码可以**免费**查看。这也意味着，**任何**将本repo的内容，包括但不限于源代码、可执行文件、技术说明文档，**擅自搬运到某些平台，特别是*CSDN*，并且付费下载或阅读**的行为**都是可耻、且违反开源协议的**。如果您发现某些平台出现了类似内容，需要付费才能查看或下载，也请开一个issue，提供相关链接。我看到后会第一时间进行处理。

注：**将本repo的任何内容搬到CSDN上是绝对不允许的。** 如果搬运到其他平台，请确保遵循开源的规定，并**保持免费**。

