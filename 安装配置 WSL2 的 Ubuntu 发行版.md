# 安装配置 WSL2 的 Ubuntu 发行版

## 1.安装WSL2

ps：由于一开始看题感觉挺懵，我试着在b站上搜索了相关方法，这是我浏览的：[Windows11下安装Linux 操作系统 | 使用WSL2安装Ubuntu | Windows10下安装Linux_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1Qb4y1a7KZ?spm_id_from=333.337.search-card.all.click&vd_source=4839fb85c1f4958be93e094d258267e5)

并搜到了这一个Microsoft官网的文档：[旧版 WSL |的手动安装步骤微软文档 (microsoft.com)](https://docs.microsoft.com/en-us/windows/wsl/install-manual)

![](https://s1.ax1x.com/2022/09/07/vHY92V.png)

并通过powershell以管理员身份运行输入代码

**dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart**

和**dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart**

完成后输入代码：**wsl --set-default-version 2**将wsl2设置为默认版本

并重启windows

![](https://s1.ax1x.com/2022/09/07/vHYkb4.png)

## 2.启动Intel virtualization technology

在开机过程中按下f2，进入bios，开启虚拟化



## 3.安装Linux发行版

点开Microsoft自带的应用商城，搜索Ubuntu并下载

![](https://s1.ax1x.com/2022/09/07/vHYZ5R.png)

进行一系列注册后完成

![](https://s1.ax1x.com/2022/09/07/vHYn8x.png)

