[<kbd>**`* 简体中文 *`**</kbd>](https://github.com/francis-zhao/quarklist#readme "读我") [<kbd>English</kbd>](https://github.com/francis-zhao/quarklist/blob/master/README.en.md "Readme")

# QuarkList

## 简介

参照 [Adblock Plus 过滤语法规则](https://help.eyeo.com/adblockplus/how-to-write-filters "如何编写过滤")编写的广告过滤套件，包含 [QuarkList](#quarklist-1) 和 [hosts](#hosts)。

<br>

## 项目

### [QuarkList](https://github.com/francis-zhao/quarklist/blob/master/dist/quarklist.txt)

一款针对中国大陆地区用户的广告过滤列表，适用于 [Adblock Plus](https://adblockplus.org/ "Adblock Plus")、[AdBlock](https://getadblock.com/ "AdBlock")、[uBlock Origin](https://github.com/gorhill/uBlock "uBlock Origin") 等浏览器通用过滤扩展。本列表作为官方列表 `EasyList` 和 `EasyList China` 的补充，可以强化网页广告拦截效果，直接点击下方的订阅链接使用最新版本。

- 通过[个人网站](https://subscribe.adblockplus.org?location=https%3A%2F%2Fn2o.io%2Fprojects%2Fquarklist%2Fdist%2Fquarklist.txt&title=QuarkList)订阅 (首选)

- 通过 [GitHub](https://subscribe.adblockplus.org?location=https%3A%2F%2Fraw.githubusercontent.com%2Ffrancis-zhao%2Fquarklist%2Fmaster%2Fdist%2Fquarklist.txt&title=QuarkList) 订阅 (不推荐，需要科学上网)

因 `jsDelivr` 自 2021 年底已停止中国大陆地区的服务，如果之前使用了此来源订阅且现在无法更新使用，建议删除后通过`个人网站`链接重新订阅。

<br>

### [hosts](https://github.com/francis-zhao/quarklist/blob/master/dist/hosts)

拦截广告域名的 hosts 规则，不仅可以用于浏览器的广告拦截，还能用于全部联网程序，但只能拦截特定的广告域名，无法编写适用性更广的过滤规则，**一般情况下不建议使用**。

将 hosts 文件中的规则替换或追加到 Windows 系统中的 `C:\Windows\System32\drivers\etc\hosts` 或 Linux 与 macOS 系统中的 `/etc/hosts` 文件中保存即可生效。

<br>
<br>

[<kbd>返回顶部</kbd>](# "返回顶部")
