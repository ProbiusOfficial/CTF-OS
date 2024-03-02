<div align="center">  
    <img src="./img/logo.png" width="70%"> 
    <br> </br>
    <p> An Integrated OS For CTF(Capture The Flag)</p>
    <p>专为CTF比赛封装的虚拟机，基于工具集封装多个版本和系统，更多选择，开箱即用！</p>
</div> 


## Why CTFos?

市面上其实有很多同类型的系统 —— 但这里的同类型指的是在安全和渗透相关的，而对于CTFs来讲，它们是臃肿的，而且都侧重在Web安全方面，并不友好。

当然，更多的情况是，在CTF比赛越来越普及的今天，它渗透到了各个行业里面，想象一下，上学打了几年CTF好不容易毕业了，跑到其他行业养老突然被领导拉着语重心长的说：“听说你上学的时候，比赛挺厉害的，正好最近我们有个行业赛，就是CTF，你上吧，顺便带带你的同事们” —— 

**本项目用于快速构建CTF的做题环境，避免CTF中各类软件环境对宿主机造成污染。**

**适用人群**：CTF入门选手，各行业从业人员，安全相关工作人员但不想在工作机上安装CTF一些奇奇怪怪的软件......

## About

系统基于 WIndows 10 22H2 10.0.19045.3803 镜像制作，使用 软媒魔方 和 Dism++ 进行了部分优化和精简，内置 Ubuntu 22.04.3 on WSL1 子系统。

## Statement

本系统中所出现的各类软件 / 工具 均来源于开源渠道，所有组件的来源均以注明 (详细见 **Detail** 部分)

由于时间和其他原因，系统并不能有效包含所有的CTF工具，不过我们会逐步更新和完善它，还请关注后续发版。

当然，如果您对系统后续更新有建议，请务必开 issues 告知我们。

本项目为 [Hello-CTF](https://github.com/ProbiusOfficial/Hello-CTF) 的子项目，大部分工具软件的选择基于 https://hello-ctf.com/ToolKit/ ,欢迎关注我们的公众号 Hello-CTF ，获取CTF相关资讯：

![Qr](./img/Qr.jpg)

## DEMO

![Desktop](./Demo/Desktop.png)

![Terminal_Design](./Demo/Terminal_Design.png)

![Ubuntu_info](./Demo/Ubuntu_info.png)

![Toolkit](./Demo/Toolkit.png)

## Detail_Beta版本(试运行)

详细见 Releases.

### 系统环境

Python 3.8.2rc2 (tags/v3.8.2rc2:777ba07, Feb 18 2020, 09:11:15) [MSC v.1916 64 bit (AMD64)]

Java 环境 jdk-1.8 (build 1.8.0_401-b10)

PHP 7.3.4

MySQL 5.7.26

Nginx 1.15.11

Apache 2.4.39

Msys2-x86_64-20240113 

gcc 13.2.0 @msys2

### WSL子系统

```
Ubuntu 22.04.3 LTS on Windows 10 x86_64
WSL 版本： 2.0.9.0
内核版本： 5.15.133.1-1
WSLg 版本： 1.0.59
MSRDC 版本： 1.2.4677
Direct3D 版本： 1.611.1-81528511
DXCore 版本： 10.0.25131.1002-220531-1700.rs-onecore-base2-hyp
Windows 版本： 10.0.19045.3803
```

**子系统工具：**

Binwalk v2.3.4 https://github.com/ReFirmLabs/binwalk/releases/tag/v2.3.4

SQLMap v1.8.2 @pip

Foremost v1.5.7

dirsearch v0.4.3.post1 @pip

exiftool @apt

zsteg https://github.com/zed-0xff/zsteg @gem

StegoVeritas https://github.com/bannsec/stegoVeritas @pip

### 工具

#### 系统工具

PHPStudy v8.1.1.3  源:https://www.xp.cn/

PixPin v1.7.5.0 源:https://pixpinapp.com/

Dism++ v10.1.1002.2 源:https://github.com/Chuyu-Team/Dism-Multi-language/releases/tag/v10.1.1002.2

Everything 源:https://www.voidtools.com/zh-cn/

分区助手 源:https://www.disktool.cn/

PCmast-软媒魔方 源:https://mofang.ruanmei.com/

#### Web

BurpSuite v2024.1.1 源:https://www.52pojie.cn//thread-1544866-1-1.html

Behinder_v4.1 源:https://github.com/rebeyond/Behinder/releases/tag/Behinder_v4.1%E3%80%90t00ls%E4%B8%93%E7%89%88%E3%80%91

Godzilla v4.0.1 源:https://github.com/BeichenDream/Godzilla/releases/tag/v4.0.1-godzilla

Ysoserial v0.0.6 源:https://github.com/frohoff/ysoserial/releases/tag/v0.0.6

jar-analyzer v2.12 源:https://github.com/jar-analyzer/jar-analyzer/releases/tag/2.12

#### 文件Hex / 编辑

ImHex v1.33.0 源:https://github.com/WerWolv/ImHex/releases/tag/v1.33.0

010EditorWin64Portable14.0 源:https://www.52pojie.cn/thread-1863194-1-4.html

#### 隐写相关

Tweakpng v1.4.6 源:https://entropymine.com/jason/tweakpng/

stegdetect-0.4-for-Windows 源:Unknown

WaterMark 源:https://www.52pojie.cn/

z3-4.12.6 源:https://github.com/Z3Prover/z3/releases/tag/z3-4.12.6

#### MISC 综合工具

随波逐流CTF编码工具 / 随波逐流 OCR识别工具 / 随波逐流224种编码图 源:http://1o1o.xyz/index.html

CTFCrackTools v4.0.7 源:https://github.com/0Chencc/CTFCrackTools/releases/tag/4.0.7

Puzzle Solver v1.0.4 源:https://github.com/Byxs20/PuzzleSolver/releases 注：为尊重项目要求，只保留了最后一个开源版本，后续的版本请按照Release中的说明自行获取

#### 取证分析

Wireshark-4.2.3-x64.exe 源:https://www.wireshark.org/download.html

LovelyMem 源:https://github.com/Tokeii0/LovelyMem/releases/tag/v0.2

BlueTeamTools 源:https://github.com/abc123info/BlueTeamTools/releases/tag/v0.92

PasswareKitForensic v2020 汉化 By Tokeii 源:NULL

#### 密码学辅助工具

CTF_AES加解密工具 / 国密SM4加解密工具 / 轩禹CTF_RSA工具3.6  源:https://space.bilibili.com/317479700

ciphey v5.14.0 @pip

Z3求解器 

#### 漏洞利用

  - Struts2_19.21.jar 源:https://github.com/abc123info/Struts2VulsScanTools
  - ThinkphpGUI-1.3-SNAPSHOT.jar 源:https://github.com/Lotus6/ThinkphpGUI/releases/tag/1.3
  - thinkphp_gui_tools 源:https://github.com/bewhale/thinkphp_gui_tools
  - ShiroExploit-Deprecated v2.51 源:https://github.com/feihong-cs/ShiroExploit-Deprecated/releases/tag/v2.51
  - ThinkPHP综合利用工具ShiroExploit v2.4.2 源:https://github.com/bewhale/thinkphp_gui_tools/releases/tag/v2.4.2

## Wallpaper

![Flag_with_Windows_color](./wallpaper/Flag_with_Windows_color.png)

![CTFos](./wallpaper/CTFos.png)

![Flag_with_Windows](./wallpaper/Flag_with_Windows.png)

![Windows_Terminal](./wallpaper/Windows_Terminal.png)

![PowerShell](./wallpaper/PowerShell.png)

![Ubuntu_Shell](./wallpaper/Ubuntu_Shell.png)