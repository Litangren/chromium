* [English](#chromium-with-ssl-vpn)
* [简体中文](#chromium浏览器)

# Chromium浏览器

直接内置翻墙代理的Google Chromium浏览器。

![](screenshot.png)

最新版本：[75.0.3766.2](https://github.com/jjqqkk/chromium/releases/tag/75.0.3766.2)

[Chromium](https://github.com/chromium/chromium)是Google Chrome浏览器的开源版本，两者共享大部分代码。新的开发和改进先通过Chromium项目完成，大约通过6周测试后再由Google官方发布，因此Chromium是Chrome先行版本。

## Windows (10/8/7)

[下载Windows版](https://github.com/jjqqkk/chromium/releases/download/75.0.3766.2/Chromium-windows-75.0.3766.2.zip)

[备用下载地址](http://167.99.163.129/Chromium-windows-75.0.3766.2.zip)

### 使用方法

下载zip文件后解压缩，从解压后目录里运行**chromium.exe**。

## macOS

[下载macOS版](https://github.com/jjqqkk/chromium/releases/download/75.0.3766.2/Chromium-mac-75.0.3766.2.zip)

[备用下载地址](http://167.99.163.129/Chromium-mac-75.0.3766.2.zip)

### 使用方法

下载zip文件后解压缩，直接得到App。由于签名问题，首次运行，按住Control点图标，从菜单里打开App。之后直接双击图标即可运行。


## 如何解决Windows版本崩溃？
[issue #78](https://github.com/jjqqkk/chromium/issues/78) Thanks [leoxxnet](https://github.com/leoxxnet)


## 如何解决缺少Google API 密钥

网上已有解决办法，实测可用：

管理员模式打开CMD输入以下三行内容

setx GOOGLE_API_KEY "AIzaSyAUoSnO_8k-3D4-fOp-CFopA_NQAkoVCLw"

setx GOOGLE_DEFAULT_CLIENT_ID "6307505647-6knmr84r2pj2leudg3pp1j0h1licd6b9.apps.googleusercontent.com"

setx GOOGLE_DEFAULT_CLIENT_SECRET "rbeWhXTLgU8oLiUeefPsEL9c"

这三行分别是：API密钥、客户端ID、客户端密钥

完成之后就可以登录谷歌账号了

登录谷歌账号后浏览英文网页会自动弹出google翻译

# Chromium with SSL VPN

Chromium with SSL VPN lets you unblock websites directly in the browser.

![](screenshot.png)

Latest version: [75.0.3766.2](https://github.com/jjqqkk/chromium/releases/tag/75.0.3766.2)

Chromium is the open source project behind the Google Chrome browser. It is a fully functional browser and also widely used by other parties to create their own browsers. Many vendors use the code in a similar manner as Google, while others simply build it as-is and release browsers with the Chromium name.

This build takes advantage of the [VPN](https://developer.chrome.com/extensions/vpnProvider) and [Proxy](https://developer.chrome.com/extensions/proxy) API developed by Google. 

## Windows 10/8/7

[Download Chromium for Windows](https://github.com/jjqqkk/chromium/releases/download/75.0.3766.2/Chromium-windows-75.0.3766.2.zip)

[Backup download site](http://167.99.163.129/Chromium-windows-75.0.3766.2.zip)

## macOS

[Download Chromium for macOS](https://github.com/jjqqkk/chromium/releases/download/75.0.3766.2/Chromium-mac-75.0.3766.2.zip)

[Backup download site](http://167.99.163.129/Chromium-mac-75.0.3766.2.zip)

## How to upgrade Chromium?

We will follow [Google's release schedule](https://chromiumdash.appspot.com/schedule) and post the binaries on the [releases](https://github.com/jjqqkk/chromium/releases) page.

Users are free to download newer versions. There will be no conflict to having two Chromium on the same computer.

## How to uninstall Chromium?

Simply delete the folder on Windows, or the app on macOS.
