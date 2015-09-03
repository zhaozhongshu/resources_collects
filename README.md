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

## TweetLanes

Tweet Lanes for Android

## weiciyuan
新浪微博Android客户端