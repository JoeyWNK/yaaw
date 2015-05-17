YAAW (汉化版)
====

[Binux](https://github.com/binux/yaaw)大大作品

一个纯粹由HTML/CSS/Javascirpt组成的 Aria2 网页前端

无需HTTP服务器，后台的或者服务端程序。你只需一个浏览器

<br />

用法
-----
1. 运行 aria2 同时启用RPC
> aria2c --enable-rpc --rpc-listen-all=true --rpc-allow-origin-all
>
> Warning: This options will not verify the identity of caller. KEEP THE ADDRESS SECRET.

2. 访问 **index.html**

3. 如果发生错误"Internal server error"，修改"JSON-RPC 路径" 的设置

提示
----
* 在页面的设置都是临时的。 **一旦 aria2 重启，设置将被重置**

* 一旦 aria2 重启，任务(包括未完成的) 将会丢失。 使用 `--save-session=路径` 来保存会话并通过 `--continue=true --input-file=路径` 来恢复会话

* 使用 `$HOME/.aria2/aria2.conf` 来保存选项

* 更多有关 aria2 信息, 访问 [Aria2 手册(英文)](http://aria2.sourceforge.net/manual/en/html/)

组件
----------
+ [Bootstrap](http://twitter.github.com/bootstrap/)
+ [mustache.js](https://github.com/janl/mustache.js)
+ [jQuery](http://jquery.com/)
+ [jQuery Storage](http://archive.plugins.jquery.com/project/html5Storage)
+ [JSON RPC 2.0 jQuery Plugin](https://github.com/datagraph/jquery-jsonrpc)

协议
-------
yaaw 遵循 GNU Lesser General Public 协议

你可以通过 http://www.gnu.org/licenses/lgpl.txt 获得一份 GNU Lesser General Public 协议的副本

favicon.ico 来自 [fangke](http://fangke.im/)