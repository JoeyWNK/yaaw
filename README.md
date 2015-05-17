YAAW (汉化版)
====

[Binux](https://github.com/binux/yaaw)大大作品

Yet Another Aria2 Web Frontend in pure HTML/CSS/Javascirpt.
一个纯粹由HTML/CSS/Javascirpt组成的 Aria2 网页前端

No HTTP server, backend or server-side program. All you need is just a browser.
无需HTTP服务器，后台的或者服务端程序。你只需一个浏览器

<br />

Usage 用法
-----
1. Run aria2 with RPC enabled
1. 运行 aria2 同时启用RPC
> aria2c --enable-rpc --rpc-listen-all=true --rpc-allow-origin-all
>
> Warning: This options will not verify the identity of caller. KEEP THE ADDRESS SECRET.

2. Visit **index.html**.
访问 **index.html**

3. Change "JSON-RPC Path" setting if "Internal server error" occurred.
3. 如果发生错误"Internal server error"，修改"JSON-RPC 路径" 的设置

Tips 提示
----
* All your settings on web is temporary. **Settings will be lost after aria2 restarted.**
* 在页面的设置都是临时的 **一旦 aria2 重启，设置将被重置**

* Tasks(including which is not finished) will be lost after aria2 restarted. Using `--save-session=SOME/WHERE` and reload with `--continue=true --input-file=SOME/WHERE` to continue.
* 一旦 aria2 重启，任务(包括未完成的) 将会丢失。 使用 `--save-session=路径` 来保存会话并通过 `--continue=true --input-file=路径` 来恢复会话

* Using `$HOME/.aria2/aria2.conf` to save your options.
* 使用 `$HOME/.aria2/aria2.conf` 来保存选项

* For more infomations about aria2, visit [Aria2 Manual](http://aria2.sourceforge.net/manual/en/html/)
* 更多有关 aria2 信息, 访问 [Aria2 手册(英文)](http://aria2.sourceforge.net/manual/en/html/)

Components 组件
----------
+ [Bootstrap](http://twitter.github.com/bootstrap/)
+ [mustache.js](https://github.com/janl/mustache.js)
+ [jQuery](http://jquery.com/)
+ [jQuery Storage](http://archive.plugins.jquery.com/project/html5Storage)
+ [JSON RPC 2.0 jQuery Plugin](https://github.com/datagraph/jquery-jsonrpc)

License 协议
-------
yaaw is licensed under GNU Lesser General Public License.
yaaw 遵循GNU Lesser General Public协议

You may get a copy of the GNU Lesser General Public License from http://www.gnu.org/licenses/lgpl.txt
你可以通过 http://www.gnu.org/licenses/lgpl.txt 获得一份 GNU Lesser General Public 协议的副本

favicon.ico by [fangke](http://fangke.im/)
favicon.ico 来自 [fangke](http://fangke.im/)