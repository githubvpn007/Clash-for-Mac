# Clash-for-Mac               
Clash for Windows for Mac，Clash for Windows for Mac教程，Clash for Windows for Mac配置说明，Clash for Mac，vpn代理


简介
----

Clash 是一个使用 Go 语言编写，基于规则的跨平台代理软件核心程序。  

Clash for Windows 通过 Clash API 来配置和控制 Clash 核心程序，便于用户可视化操作和使用。  

Clash for Windows for Mac 是 Clash for Windows 作者的另一款作品。所以它的全名应该叫 Clash for Windows for Mac (很怪)  



下载安装
----

[下载地址](https://archive.org/download/clash_for_windows_pkg)     [备用地址](https://web.archive.org/web/20231030023222/https://github.com/Fndroid/clash_for_windows_pkg/releases)

从releases界面下载.dmg格式的文件进行安装。  

打开下载完成的 dmg 映像文件，将 Clash for Windows 添加到应用程序文件夹中。  

![](https://i.postimg.cc/wMtrdgWG/1.png)  

如果macOS阻止运行该软件，请执行以下操作：  

由于 macOS 默认情况下只允许运行可信任签名的应用，如果 macOS 阻止运行该软件，请打开 macOS 终端，在新建的终端 Shell 中输入：  

`sudo spctl --master-disable`

![](https://i.postimg.cc/9FD2WjRV/2.png)  

由于调用了sudo权限，你可能需要输入密码，会输出如下提示：  

`Password:`

![](https://i.postimg.cc/nzV8N8by/3.png)  


此时你需要输入密码，在 Shell 中输入的密码是不可见的，输入完毕后请按回车键。  




<br/>
<br/>

添加订阅
----

1.如果没有订阅链接[请看这里](https://github.com/githubvpn007/v2rayNvpn#%E8%8A%82%E7%82%B9%E5%88%86%E4%BA%AB)  

2.打开 Clash for Windows for Mac 后，点击窗口左侧的 Profiles (配置文件)。

![](https://i.postimg.cc/7YGFFMdZ/4.png)   



3.在 Profiles 页面顶部，输入 Clash 配置订阅链接，然后点击 Download 下载配置文件。  

![](https://i.postimg.cc/wxGK4bWr/5.png)   


4.下载成功后，Clash for Windows 将自动切换配置文件。


![](https://i.postimg.cc/TYzzf5vq/6.png)   



<br/>
<br/>


开启代理
---

1.设置代理模式  

点击窗口左侧的 Proxies (代理)。  

默认情况下，Clash 使用 Rule (规则) 模式。不推荐选择 Global (全局) 与 Direct (直连) 模式。  

全局（Global）：所有请求直接发往代理服务器  
规则（Rule）：所有请求根据配置文件规则进行分流  
直连（Direct）：所有请求直接发往目的地  
PAC模式:这个模式是根据PAC文件，来判断请求是否要经过代理。


Clash 支持通过策略组，对不同的网站使用不同的策略。合理使用分流可以提升使用体验。

![](https://i.postimg.cc/fyF63Jts/7.png)   



2.开启 System Proxy (系统代理)，即可科学上网。  


![](https://i.postimg.cc/bw1KJYzX/8.png)   


<br/>
<br/>



### 本项目不做VPN分享，如果您希望获得最佳的科学上网方案 [点击这里](https://github.com/githubvpn007/v2rayNvpn)  

### 如果你想知道clash/ss/ssr/v2ray/trojan 的区别的话 [请点这里](https://github.com/githubvpn007/proxy)

