# Awesome Cloudflare [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re) [<img src="https://img.techrk1688.eu.org/file/e44951f61086ae4dc9591.png" width="250" align="right" alt="Cloudflare">](https://www.cloudflare.com)

> 精选的互联网之光 [Cloudflare](https://www.cloudflare.com) 开源项目、指南、博客和其他资源列表。

被称为赛博菩萨的 Cloudflare 提供内容交付网络 （CDN） 服务、DDoS 缓解、互联网安全和分布式域名服务器 （DNS） 服务，位于访问者和 Cloudflare 用户的托管提供商之间，充当网站的反向代理。

本仓库只收录基于Cloudflare的开源工具，为独立开发者早期摸索期提供一个省心省时的工具集，持续整理中……

**收录标准：**

- 帮助但不限于独立开发者提升开发效率
- 帮助但不限于独立开发者降低成本
- 足够简单便捷

欢迎提 pr 和 issues 更新。

## Contents

- [图床](#image-host)
- [邮箱](#emial)
- [博客](#blog)
- [短链](#short-link)
- [Other](#other)

## 图床

| 名称 | 特性 |在线地址 | 状态|
| --- | --- | --- |---|
| [Telegraph-Image-Hosting](https://github.com/missuo/Telegraph-Image-Hosting) |使用 Telegraph 构建免费图像托管 | | 不再维护|
| [cf-image-hosting](https://github.com/ifyour/cf-image-hosting) |在 Telegraph 上免费无限制地托管图像，部署在 Cloudflare 上。 | <https://images.mingming.dev> |维护中|
| [img-mom](https://github.com/beilunyang/img-mom) |基于 Cloudflare Workers 运行时构建, 轻量使用完全免费，支持多种图床（Telegram/Cloudfalre R2/Backblaze B2, 更多图床正在支持中），快速部署。使用 Wrangler 可快速实现自部署 | |维护中|
| [workers-image-hosting](https://github.com/iiop123/workers-image-hosting) |基于cloudflare workers数据存储于KV的图床 | |维护中|
| [Telegraph-Image](https://github.com/cf-pages/Telegraph-Image) |免费图片托管解决方案，Flickr/imgur 替代品。使用 Cloudflare Pages 和 Telegraph。 | <https://im.gurl.eu.org/> |维护中|
| [cloudflare-worker-image](https://github.com/ccbikai/cloudflare-worker-image) |使用 Cloudflare Worker 处理图片, 依赖 Photon，支持缩放、剪裁、水印、滤镜等功能。 |  |维护中|

## 邮箱

| 名称 | 特性 |在线地址 | 状态|
| --- | --- | --- |---|
| [vmail](https://github.com/oiov/vmail) |利用 worker 的 KV 作为数据库搭建博客 | <https://vmail.dev/> | 维护中|
| [smail](https://github.com/akazwz/smail) |利用 workers+github 搭建博客系统。| <https://smail.pw/> | 维护中 |
| [Email.ML](https://email.ml/) | 一个运行在 Cloudflare 网络中的临时邮箱|  | 未开源 |
| [cloudflare_temp_email](https://github.com/dreamhunter2333/cloudflare_temp_email) | 使用 cloudflare 免费服务，搭建临时邮箱|  <https://temp-email.dreamhunter2333.xyz/> | 维护中 |

## 博客

| 名称 | 特性 |在线地址 | 状态|
| --- | --- | --- |---|
| [cloudflare-workers-blog](https://github.com/gdtool/cloudflare-workers-blog) |一个开源的临时邮件服务，该项目基于 Cloudflare worker + turso sqlite + Vercel ，全程免费实现，轻松拥有专属的临时邮件网站 | <https://blog.gezhong.vip/> | 维护中|
| [cloudflare-workers-blog](https://github.com/kasuganosoras/cloudflare-worker-blog) |Cloudflare workers + Github 实现的动态博客系统，使用边缘计算，无需服务器| | 好像是不维护了|

## 短链

| 名称 | 特性 |在线地址 | 状态|
| --- | --- | --- |---|
| [short](https://github.com/igengdu/short/) |一个使用 Cloudflare Pages 创建的 URL 缩短器。| <https://d.igdu.xyz/> | 维护中|
| [Url-Shorten-Worker](https://github.com/crazypeace/Url-Shorten-Worker) |使用秘密路径访问操作页面。支持自定义短链。API 不公开服务。页面缓存设置过的短链。长链接文本框预搜索localStorage。增加删除某条短链的按钮。增加读取KV的按钮。变身网络记事本 Pastebin。变身图床 Image Hosting。A URL Shortener created using Cloudflare worker and KV| [<https://smail.pw/>](https://urlsrv.crazypeace.workers.dev/bodongshouqulveweifengci) | 维护中 |
| [duanwangzhi](https://github.com/Closty/duanwangzhi) |无需服务即可缩短您的链接，因为它基于 Cloudflare 工作人员功能，具有极简风格。|  | 好像是不维护了 |

## Other

| 名称 | 特性 |在线地址 | 状态|
| --- | --- | --- |--- |
| [analytics_with_cloudflare](https://github.com/yestool/analytics_with_cloudflare) |免费开源网页访客计数器, Webviso 是一个基于Cloudflare worker服务+Cloudflare D1数据库实现的完全免费的在线web访客统计服务。 功能与目前常用的 不蒜子 - 极简网页计数器 相同。Webviso完全开源，你可以实现自定义需求。 基于Cloudflare的微服务架构可快速自行部署上线。 | |维护中|
| [silk-privacy-pass-client](https://chromewebstore.google.com/detail/silk-privacy-pass-client/ajhmfdgkijocedmfjonnpjfojldioehi) |频繁出现Cloudflare人机验证，可以用这个Cloudflare官方插件解决，装了之后，再也不会动不动跳出人机验证了。 | | 维护中|
| [WARP-Clash-API](https://github.com/vvbbnn00/WARP-Clash-API) |该项目可以让你通过订阅的方式使用WARP+，支持Clash、Shadowrocket等客户端。项目内置了 刷取WARP+流量的功能，可以让你的WARP+流量不再受限制（每18秒可获得1GB流量），同时， 配备了IP选优功能。支持Docker compose 一键部署，无需额外操作，即可享受你自己的WARP+私 有高速节点！ | |维护中|
| [ip-api](https://github.com/ccbikai/ip-api) |利用 Cloudflare Workers / Vercel Edge / Netlify Edge 快速搭一个获取 IP 地址和地理位置信息的接口。|<https://html.zone/ip> |维护中|
| [ChatGPT-Telegram-Workers](https://github.com/TBXark/ChatGPT-Telegram-Workers) |轻松在 Cloudflare Workers 上部署您自己的 Telegram ChatGPT 机器人，有详细的视频和图文教程，搭建过程也不复杂，小白也能上手。| |维护中|
| [RSSWorker](https://github.com/yllhwa/RSSWorker) |RSSWorker 是一个轻量级的 RSS 订阅工具，可以部署在 Cloudflare Worker 上。| |维护中|
