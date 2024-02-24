**The repository has been archived due to: [README.md](https://github.com/Z-Siqi/Clash-for-Windows_Chinese/blob/main/CFW/README.md)**


***

# Clash for Windows Chinese<img src="https://github.com/Z-Siqi/Clash-for-Windows_Chinese/blob/main/image/image_clash.png?raw=true" width="30" height="30">
### Clash 汉化版

**提供clash for windows的汉化版, 汉化补丁以及汉化版Clash安装程序**

效果图

[![photo](https://github.com/Z-Siqi/Clash-for-Windows_Chinese/assets/77391690/cbc8698c-7e3c-4ff2-b2ed-4bccae1e6251?raw=true)](https://github.com/Z-Siqi/Clash-for-Windows_Chinese/releases/)
> 效果图的版本可能不是当前最新兼容的

**支持的clash版本:**

[0.15.3](https://github.com/Z-Siqi/Clash-for-Windows_Chinese/releases/tag/CFW-V0.15.3_CN-V4)
~
[当前的最新兼容](https://github.com/Z-Siqi/Clash-for-Windows_Chinese/releases/latest)

**基本特征&介绍:**

* 使用安装程序(Clash.for.Windows.Setup. ** . ** . ** .exe)安装的汉化版CFW将劫持更新，之后可直接通过应用内置的更新方式进行汉化版/软件更新
* 使用安装包(Clash.for.Windows- ** . ** . ** -win.7z)请不要在解压时选择解压到当前文件夹，否则软件相关的所有文件将放到当前所在文件夹
* app.asar需要替换掉对应版本的原版app.asar以完成汉化
* 使用7z格式压缩包(app.7z)需要先进行解压，然后提取里面的app.asar并替换掉原有文件以完成汉化，即在节省流量

**<details><summary>下载前你需要知晓的内容:</summary>**

  **下载将代表你对以下内容无任何异议**

**非官方版本，Unofficial！** 

*简单来说，这个库提供的Clash for Windows是修改过的，请在向原版Clash for Windows反馈漏洞前先更换回原版*

**修改的方式/内容大致说明列表**

    对Clash for Windows进行的修改:
      1, 修改"app.asar"文件中的"renderer.js"
      2, 修改"app.asar"文件中的"main.js"
      3, 修改"app.asar"文件中的"zh-cn.js"
    对Clash for Windows植入的第三方链接:
      1, https://github.com/Z-Siqi/Clash-for-Windows_Chinese-Attached
    对app.asar替换的文件:
      1, app.asar\dist\electron\static\*
    汉化的方式
      通过Notepad++进行替换 (已被淘汰)
        手动替换用表位置:
          Clash-for-Windows_Chinese/chinese_file/Clash_Sinicization_Comparison_Table
        下载链接:
          https://notepad-plus-plus.org/downloads/
      通过Replace Pioneer的Batch Rnuuer工具配合替换表进行批量替换
        替换表的位置:
          Clash-for-Windows_Chinese/chinese_file/Auto/main-chinese
          Clash-for-Windows_Chinese/chinese_file/Auto/renderer-chinese
        下载链接
          https://www.mind-pioneer.com/
      zh-cn.js的汉化方式:
        将文件中的"后"改为"前"
        在app.asar中的位置:
          app.asar\node_modules\moment\locale\zh-cn.js
    封包方式
      安装程序的封包程序:
        简易封包工具_3.2.0.1.exe (已被淘汰)
        Inno Setup Compiler
          下载链接:
            https://jrsoftware.org/isdl.php
      .7z扩展名的封包程序:
        7-zip (已弃用)
        下载链接:
          https://7-zip.org/
        NanaZip
        下载链接:
          In the Microsoft Store



### 快速导航
[前往汉化下载界面](https://github.com/Z-Siqi/Clash-for-Windows_Chinese/releases)

[前往下载机场引流推广版 (去广告和更新检测)](https://github.com/Z-Siqi/CFW-custom-made)

[前往原版Clash for Windows下载界面](https://github.com/Fndroid/clash_for_windows_pkg/releases)

#### 能够解压7z格式的软件

[NanaZip](https://github.com/M2Team/NanaZip) *(兼容Windows11)*

[7-Zip](https://www.7-zip.org/)

[WinRAR](https://www.rarlab.com/)

