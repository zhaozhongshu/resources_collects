# resources_collects

## Java Bindings for V8
>java/Android/v8

https://github.com/eclipsesource/J2V8
J2V8 is a set of Java bindings for V8. J2V8 focuses on performance and tight integration with V8. It also takes a 'primitive first' approach, meaning that if a value can be accessed as a primitive, then it should be. This forces a more static type system between the JS and Java code, but it also improves the performance since intermediate Objects are not created.

## tabris-js
>js/android/hybird app

https://github.com/eclipsesource/tabris-js

>Native development in JavaScript 使用js开发

Tabris.js is a mobile framework that lets you develop native iOS and Android apps from a single code base written entirely in JavaScript. When HTML5 doesn’t cut it - Tabris.js will give you an easy path to native apps while building upon your existing JavaScript knowledge.
https://tabrisjs.com/examples

>No WebViews! 没有使用webview

Tabris.js does not use WebViews for rendering the UI. Instead it creates native widgets on the mobile platform via a JavaScript to native bridge. This also enables the quick develop / deploy cycle that you know from web development

>Leverage JavaScript APIs 支持XMLHttpRequest和2d绘图、underscore.js

While Tabris.js does not use WebViews, you are more than welcome to use existing JavaScript libraries, node modules and Cordova plugins to build your apps. Tabris.js implements many APIs core to web applications, e.g. XMLHttpRequest or the 2d canvas.

Create gorgeous graphs with chart.js, easily integrate underscore.js or access device features with Cordova device.

## react-native
>android/ios/js/hybird

A framework for building native apps with React. http://facebook.github.io/react-native/
react在Android、IOS中的实现，Android版本现在还没实现

## Stetho
Stetho是Facebook出品的一个强大的Android调试工具，使用该工具你可以在Chrome Developer Tools查看App的布局，网络请求，sqlite，preference，一切都是可视化的操作，无须自己在去使用adb，也不需要root你的设备。使用的方式很简单，配置好之后，在Chrome地址栏输入chrome://inspect （哈哈，和webview 远程调试的方式一样）

## libphenom
>linux/event framework/C

Facebook开发，An eventing framework for building high performance and high scalability systems in C.
Linux下使用epoll、BSD下使用kqueue

## Mcrouter 
>memcached/c

Facebook开发，Mcrouter is a memcached protocol router for scaling memcached (http://memcached.org/) deployments. It's a core component of cache infrastructure at Facebook and Instagram where mcrouter handles almost 5 billion requests per second at peak.
一句话，就是memcached的服务器router，将数据库请求路由到一组后端服务器上去

## Proxygen
>C++

Facebook开发，一个http库的C++抽象，可以用来构建http服务器、client、代理服务器，支持HTTP/1.1, SPDY/3, and SPDY/3.1. HTTP/2

## watchman
>C++

A file watching service.
facebook开发，用于监控文件改动，并执行指定动作,例如：
监控指定一个目录，并设置一个名称为buildme的触发器，该触发器会在css文件变化时调用工具minify-css编译该css

## fresco
>android/java

Android下的图片加载模块

## rocksdb
与leveldb一样，是一个嵌入式的key-value数据库，C++实现
https://github.com/facebook/rocksdb

## TweetLanes

Tweet Lanes for Android
https://github.com/chrislacy/TweetLanes

## weiciyuan
新浪微博Android客户端
https://github.com/qii/weiciyuan

## Ghost博客
号称史上做好用的博客系统，nodejs开发
https://github.com/TryGhost/Ghost博客

## libwebsockets

websocket的C++的标准实现，https://github.com/warmcat/libwebsockets

## RedisDesktopManager

https://github.com/uglide/RedisDesktopManager
图形化redis client程序，基于QT开发

## emqttd

https://github.com/emqtt/emqttd
基于erlang的高性能mqtt broker

## mqttc

https://github.com/emqtt/mqttc
基于C实现的mqtt client

## TeamTalk

https://github.com/mogujie/TeamTalk
一个企业级IM解决方案，支持win、android、linux、macos等client
以后要做消息服务器、P2P都可以参考一下，后台使用C++开发

## faye

https://github.com/faye/faye
一个非常好用的pub sub消息服务器，记忆Node.js开发

## proxychains
https://github.com/haad/proxychains

proxychains - a tool that forces any TCP connection made by any given application to follow through proxy like TOR or any other SOCKS4, SOCKS5 or HTTP(S) proxy. Supported auth-types: "user/pass" for SOCKS4/5, "basic" for HTTP. http://proxychains.sourceforge.net/
ProxyChains is a UNIX program, that hooks network-related libc functions
  in dynamically linked programs via a preloaded DLL and redirects the
  connections through SOCKS4a/5 or HTTP proxies.


## badvpn
https://github.com/ambrop72/badvpn

NCD scripting language, tun2socks proxifier, P2P VPN

>Tun2socks network-layer proxifier

The tun2socks program "socksifes" TCP connections at the network layer. It implements a TUN device which accepts all incoming TCP connections (regardless of destination IP), and forwards the connections through a SOCKS server. This allows you to forward all connections through SOCKS, without any need for application support. It can be used, for example, to forward connections through a remote SSH server.

>Peer-to-peer VPN

The VPN part of this project implements a Layer 2 (Ethernet) network between the peers (VPN nodes). The peers connect to a central server which acts as a communication proxy allowing the peers to establish direct connections between each other (data connections). These connections are used for transferring network data (Ethernet frames), and can be secured with a multitude of mechanisms. Notable features are:

> UDP and TCP transport

Converges very quickly after a new peer joins
IGMP snooping to deliver multicasts efficiently (e.g. for IPTV)
Double SSL: if SSL is enabled, not only do peers connect to the server with SSL, but they use an additional layer of SSL when exchanging messages through the server
Features related to the NAT problem:
Can work with multiple layers of NAT (needs configuration)
Local peers inside a NAT can communicate directly
Relaying as a fallback (needs configuration)

## libtorrent
https://github.com/arvidn/libtorrent
libtorrent is an open source C++ library implementing the BitTorrent protocol, along with most popular extensions, making it suitable for real world deployment. It is configurable to be able to fit both servers and embedded devices.

The main goals of libtorrent are to be efficient and easy to use.

See libtorrent.org for more detailed build and usage instructions.

To build with boost-build, make sure boost and boost-build is installed and run:

b2
In the libtorrent root. To build the examples, run b2 in the examples directory.

See building.html for more details on how to build and which configuration options are available. For python bindings, see the python docs.


## redsocks
http://darkk.net.ru/redsocks/
transparent socks redirector
This tool allows you to redirect any TCP connection to SOCKS or HTTPS proxy using your firewall, so redirection is system-wide.
类似透明代理

## tun2socks
un2socks is used to "socksify" TCP (IPv4 and IPv6) connections at the network layer. It implements a TUN virtual network interface which accepts all incoming TCP connections (regardless of destination IP), and forwards them through a SOCKS server. This allows you to forward all connections through SOCKS, without any need for application support. It can be used, for example, to forward connections through a remote SSH server or through Tor. Because of how it works, it can even be installed on a Linux router to transparently forward clients through SOCKS.
https://code.google.com/p/badvpn/wiki/tun2socks
说到代理，ssh也支持代理，ssh client可以向其他人开代理

## ProxyChains
http://proxychains.sourceforge.net/

About proxychains tool: 
     * It's a proxifier.
     * Latest version: 3.1 
     * Dedicated OS: Linux and other Unices.
     * Allows TCP and DNS tunneling through proxies. 
     * Supports HTTP, SOCKS4 and SOCKS5 proxy servers.
     * Different proxy types can be mixed in the same chain.
     * Proxy chain: user-defined list of proxies chained together.

Usability :
     * Run any program through proxy server. 
     * Access the Internet from behind a restrictive firewall.
     * Hide your IP
     * Run SSH, telnet, wget, ftp, apt, vnc, nmap through proxy servers.
     * Access Intranets (192.168.*.*/10.*.*.*) from outside through reverse proxy.
让很多不支持某代理的程序通过代理上网

## Multi-Generator
http://www.kobore.net/soft/MGEN/mgen.html
可以生成实时的TCP/IP流量，用来测试网络性能
The toolset generates real-time traffic patterns so that the network can be loaded in a variety of ways.  The generated traffic can also be received and logged for analyses.  Script files are used to drive the generated loading patterns over the course of time. These script files can be used to emulate the traffic patterns of unicast and/or multicast UDP/IP applications.  The receive portion of this tool set can be scripted to dynamically join and leave IP multicast groups.  MGEN log data can be used to calculate performance statistics on throughput, packet loss rates, communication delay, and more.  MGEN currently runs on various Unix-based (including MacOS X) and WIN32 platforms

## CTelnet
telnet开源程序

## gh0st
https://github.com/sincoder/gh0st

## A-Protect
A-Protect Anti Rootkit Tool
A盾工具

## SoftEtherVPN
https://github.com/SoftEtherVPN/SoftEtherVPN
A Free Cross-platform Multi-protocol VPN Software, developed by SoftEther VPN Project at University of Tsukuba, Japan.

## socks5_c
https://github.com/hmgle/socks5_c
一个轻量级的 socks5 代理, 带简单加密传输功能, 可穿透 GFW

## wke
3D Web UI. Web and Flash Embedded in 3D games, based on WebKit http://wke.sf.net
https://github.com/BlzFans/wke
webkit的深度裁剪，差不多2MB左右，用于嵌入网页和flash

## Torque3D
一款3D游戏引擎
https://github.com/GarageGames/Torque3D

## NTLM Authorization Proxy Server
NTLM认证代理服务器
http://ntlmaps.sourceforge.net/

## 3proxy
3Proxy tiny free proxy server is really tiny cross-platform (Win32/Win64&Unix) freeware proxy servers set. It includes HTTP proxy with HTTPS and FTP support, SOCKSv4/SOCKSv4.5/SOCKSv5 proxy (socks/socks.exe), POP3 proxy, SMTP proxy, AIM/ICQ proxy (icqpr/icqpr.exe), MSN messenger / Live messenger proxy (msnpr/msnpr.exe), FTP proxy, caching DNS proxy, TCP and UDP portmappers.

## Cntlm
对于那些使用NTLM进行身份验证的网络代理环境（即设置上除需要代理主机和端口之外还需要提供域用户和密码）来说，通过代理上网是一件头痛的事情，这主要是因为很多软件不支持NTLM验证的代理（比如目前的GIT就不能支持NTLM验证，即使在代理中指定了域帐号和密码，在连接过程中依然报： Received HTTP code 407 from proxy after CONNECT ，说明验证并未通过），如果有这样一种工具能封装NTLM验证然后对外提供普通的HTTP代理服务，那么第三方应用就可以通过配置普通的代理访问网络了，这就是Cntlm (项目官网：http://cntlm.sourceforge.net/）所要解决的问题！ 由于Cntlm也有linux版本，这意味着在linux系统上通过NTLM身份验证的网络代理也是可行的。本文原文出