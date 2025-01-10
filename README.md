**The repository has been archived due to: [README.md](https://github.com/Ruflix/ClashForWindows/blob/main/README.md)**


***

# Clash for Windows Chinese<img src="https://github.com/Z-Siqi/Clash-for-Windows_Chinese/blob/main/image/image_clash.png?raw=true" width="30" height="30">
### Clash 汉化版

**提供clash for windows的汉化版, 汉化补丁以及汉化版Clash安装程序**

效果图

[![photo](https://github.com/Z-Siqi/Clash-for-Windows_Chinese/assets/77391690/cbc8698c-7e3c-4ff2-b2ed-4bccae1e6251?raw=true)](https://github.com/Z-Siqi/Clash-for-Windows_Chinese/releases/)
> 效果图的版本可能不是当前最新兼容的


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

**重要内容**

    ----------------------------------------------------
    * Important, You MUST agree!
    * 此项目不为中国大陆地区提供任何帮助与支持
    * 赞助商的一切内容与该库无关
    * 该库不承担由使用者造成的任何行为
    * 该库的所有内容仅存在于GitHub
    * 此汉化版适用于Clash for Windows免责声明的 1 ~ 6 条
    ----------------------------------------------------


**免责声明**

    免责声明如下:
      1. 本软件仅供学习和研究网络技术之用，用户必须遵守所在地区的法律法规，不得用于非法用途，本软件不对任何人的行为负责。 

      2. 用户在使用本软件时必须严格遵守所在国家/地区的法律、法规和政策。 因违反有关法律、法规和政策而导致的任何后果或责任由用户自行承担。

      3. 本软件不负责传输内容。 因此，如因使用本软件而产生任何问题或后果，由用户自行承担全部责任。

      4. 如本软件违反用户所在国家/地区的任何法律法规，用户必须立即停止使用并承担相应的法律责任。

      5. 用户在使用本软件时，即承认并同意本软件不能保证网络的稳定性、准确性、及时性和安全性。 因网络拥塞、防火墙限制、DNS污染、运营商干扰等原因造成的连接问题或无法连接，本软件不承担任何责任。

      6. 本软件不提供技术支持，对因用户使用本软件而造成的任何直接或间接损失，包括但不限于财产损失、数据丢失及其他形式的损失不承担任何责任。
</details>

*** 

#### 赞助商的广告

购买小火箭、圈X、Google voice👉[苹果小店](https://shop.applejidi.com)

***
### 快速导航
[前往汉化下载界面](https://github.com/Ruflix/ClashForWindows/releases)

[前往下载机场引流推广版 (去广告和更新检测)](https://github.com/Ruflix/CFW-custom-made)

[~~前往原版Clash for Windows下载界面（已删库）~~](https://github.com/Fndroid/clash_for_windows_pkg/releases)

#### 能够解压7z格式的软件

[NanaZip](https://github.com/M2Team/NanaZip) *(兼容Windows11)*

[7-Zip](https://www.7-zip.org/)

[WinRAR](https://www.rarlab.com/)
