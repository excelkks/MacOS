## Mac OS recovery
重装MacOS后快速恢复，以及记录一些好用的软件
### 1. install v2rayx

[Cenmrev/V2RayX](https://github.com/Cenmrev/V2RayX/releases)

### 2. install oh-my-zsh

```shell
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

### 3. install brew

```shell
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```

### 4. install software

```shell
brew cask install qq wechat google-chrome iterm2 typora iina microsoft-office the-unarchiver sharemouse mos visual-studio-code karabiner-elements
```
### 5. sharemouse
可以多台电脑共享一套鼠键，包括可以在Window和MacOS下共享，基础功能免费 MacOS下安装
```shell
brew cask intall sharemouse
```
Window下安装
[share mouse](sharemouse.com/download/)

#### 6. confast driver
目前，intel无线网卡黑苹果还无法完美驱动，先使用confast USB无线网卡过渡。
驱动下载地址[confast driver](https://drive.google.com/open?id=1NwWyhxOjU10TMzpzCTzn0MDXc0OS_ai7)

### 7. resolution(HIDPI)
#### 7.1 hackintool
利用[hackintool](https://drive.google.com/drive/folders/1Ulo427KkEraXjpMlGLKhfyxf2VJoPO34?usp=sharing)生成显示器配置文件。具体用法可以参考[黑果小兵的blog](https://blog.daliansky.net/Intel-FB-Patcher-tutorial-and-insertion-pose.html)

#### 7.2 one-key-hidpi
除了利用hackintool外，也可以用[one-key-hidpi](https://github.com/xzhih/one-key-hidpi)一键完成HIDPI的设置

#### 7.3 resolution setting
选择分辨率可以在设置-显示器中设置，也可以使用软件[RDM](https://drive.google.com/file/d/1nfu4Qqi9TKPUiUWhbJGZqeVlUIRLWb0g/view?usp=sharing)设置

### 8. 洗白黑苹果
如果能用facetime, iMessage就不用洗白。[洗白工具](https://drive.google.com/file/d/1ojnHpfgmKA9BIMn3MRTLVl-ThEUcq670/view?usp=sharing)

### 9. 其他共具
- [USB网络共享](https://drive.google.com/file/d/1aEw-NL4FbZrT-CnXfET-Buao0VU6OCnH/view?usp=sharing)
- [Kext Utility](https://drive.google.com/file/d/1iWS7MM1cdbZjjWQuDtSiwnbU5sMdJjBB/view?usp=sharing)
- 字体[consolas](https://drive.google.com)

### 10. 改建
将shift改为F13键，再将输入法切换键设置为F13.
改建方法，按照karabiner-elements，打开设置[ 网站 ](https://genesy.github.io/karabiner-complex-rules-generator/#eyJ0aXRsZSI6IlByZXNzIGxlZnRfc2hpZnQgYWxvbmUgcHJvZHVjZXMgRjEzIiwicnVsZXMiOlt7ImRlc2NyaXB0aW9uIjoiUHJlc3MgbGVmdF9zaGlmdCBhbG9uZSBwcm9kdWNlcyBGMTMiLCJtYW5pcHVsYXRvcnMiOlt7InR5cGUiOiJiYXNpYyIsImZyb20iOnsia2V5X2NvZGUiOiJsZWZ0X3NoaWZ0IiwibW9kaWZpZXJzIjp7Im9wdGlvbmFsIjpbImFueSJdfX0sInRvIjpbeyJrZXlfY29kZSI6ImxlZnRfc2hpZnQifV0sInRvX2lmX2Fsb25lIjpbeyJrZXlfY29kZSI6ImYxMyJ9XX1dfV19)。如果网站失效，参考[ sspai ](https://sspai.com/post/43324)
