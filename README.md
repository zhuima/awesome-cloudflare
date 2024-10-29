<div align="center">

<h1 align="center">Awesome Cloudflare <img src="https://img.shields.io/github/stars/zhuima/awesome-cloudflare?label=Stars" alt="stars"></h1>

本仓库只收录基于Cloudflare的开源工具，为独立开发者早期摸索期提供一个省心省时的工具集，持续整理中……

[中文](./README.md) / [English](./README-EN.md) / [Español](./README-ES.md) / [Deutsch](./README-DE.md)

![awesome-cloudflare](./docs/awesome-cloudflare.svg)

</div>

# [<img src="https://img.techrk1688.eu.org/file/e44951f61086ae4dc9591.png" width="250" align="right" alt="Cloudflare">](https://www.cloudflare.com)

> [![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&vCenter=true&multiline=true&random=false&height=80&lines=%E7%B2%BE%E9%80%89%E7%9A%84%E4%BA%92%E8%81%94%E7%BD%91%E4%B9%8B%E5%85%89+Cloudflare+%E5%BC%80%E6%BA%90%E9%A1%B9%E7%9B%AE;%E3%80%81%E6%8C%87%E5%8D%97%E3%80%81%E5%8D%9A%E5%AE%A2%E5%92%8C%E5%85%B6%E4%BB%96%E8%B5%84%E6%BA%90%E5%88%97%E8%A1%A8%E3%80%82)](https://git.io/typing-svg)

被称为赛博菩萨的 Cloudflare 提供内容交付网络 （CDN） 服务、DDoS 缓解、互联网安全和分布式域名服务器 （DNS） 服务，位于访问者和 Cloudflare 用户的托管提供商之间，充当网站的反向代理。

**收录标准：**

- 帮助但不限于独立开发者提升开发效率
- 帮助但不限于独立开发者降低成本
- 足够简单便捷

欢迎提 pr 和 issues 更新。 部署或操作过程中有任何问题可以提issue或者私信咨询～

## 在线版本

[Awesome Cloudflare 在线导航](https://cloudflare.chuhai.tools)

## Contents

- [Contents](#contents)
- [图床](#图床)
- [邮箱](#邮箱)
- [博客](#博客)
- [脚手架](#脚手架)
- [短链](#短链)
- [网站分析](#网站分析)
- [隧道](#隧道)
- [加速](#加速)
- [文件分享](#文件分享)
- [测速](#测速)
- [监控](#监控)
- [文章](#文章)
- [其他](#其他)
- [教程](#教程)
- [群组](#群组)
- [捐赠](#捐赠)
- [Contributors](#contributors)
- [Star History](#star-history)

## 图床

| 名称 | 特性 |在线地址 | 状态|
| --- | --- | --- |---|
| [Telegraph-Image-Hosting](https://github.com/missuo/Telegraph-Image-Hosting) |使用 Telegraph 构建免费图像托管 | | 不再维护|
| [cf-image-hosting](https://github.com/ifyour/cf-image-hosting) |在 Telegraph 上免费无限制地托管图像，部署在 Cloudflare 上。 | <https://images.mingming.dev> |维护中|
| [img-mom](https://github.com/beilunyang/img-mom) |基于 Cloudflare Workers 运行时构建, 轻量使用完全免费，支持多种图床（Telegram/Cloudflare R2/Backblaze B2, 更多图床正在支持中），快速部署。使用 Wrangler 可快速实现自部署 | |维护中|
| [workers-image-hosting](https://github.com/iiop123/workers-image-hosting) |基于cloudflare workers数据存储于KV的图床 | |维护中|
| [Telegraph-Image](https://github.com/cf-pages/Telegraph-Image) |免费图片托管解决方案，Flickr/imgur 替代品。使用 Cloudflare Pages 和 Telegraph。 | <https://im.gurl.eu.org/> |维护中|
| [cloudflare-worker-image](https://github.com/ccbikai/cloudflare-worker-image) |使用 Cloudflare Worker 处理图片, 依赖 Photon，支持缩放、剪裁、水印、滤镜等功能。 |  |维护中|
| [tgState](https://github.com/csznet/tgState) |使用Telegram作为存储的文件外链系统，不限制文件大小和格式。 | <https://tgstate.vercel.app>  |维护中|
| [telegraph-Image](https://github.com/x-dr/telegraph-Image) |一个图床。 | <https://img.131213.xyz/> |维护中|
| [roim-picx](https://github.com/roimdev/roim-picx) |基于CloudFlare Pages和R2实现的免费图床。 |  |维护中|
| [CloudFlare-ImgBed](https://github.com/MarSeventh/CloudFlare-ImgBed) |基于CloudFlare和Telegraph的免费图床，本仓库基于<https://github.com/cf-pages/Telegraph-Image> ，是原项目前端页面的重制版。开源、清晰、美观、动画丝滑、玩法多样！ |  <https://demo-cloudflare-imgbed.pages.dev/> |维护中|


## 邮箱

| 名称 | 特性 |在线地址 | 状态|
| --- | --- | --- |---|
| [vmail](https://github.com/oiov/vmail) |📫 Open source temporary email tool. 开源临时邮箱工具，支持收发邮件。 | <https://vmail.dev/> | 维护中|
| [smail](https://github.com/akazwz/smail) |临时邮箱服务| <https://smail.pw/> | 维护中 |
| [Email.ML](https://email.ml/) | 一个运行在 Cloudflare 网络中的临时邮箱|  | 未开源 |
| [cloudflare_temp_email](https://github.com/dreamhunter2333/cloudflare_temp_email) | 使用 cloudflare 免费服务，搭建临时邮箱，D1 作为数据库，带有前端及后端，支持多国语言及自动回复功能，支持附件 IMAP SMTP|  <https://mail.awsl.uk/> | 维护中 |
| [mail2telegram](https://github.com/TBXark/mail2telegram) | 这是一个基于 Cloudflare Email Routing Worker 的 Telegram Bot，可以将电子邮件转换为 Telegram 消息。您可以将任何前缀的收件人的电子邮件转发到 Bot，然后将创建一个具有无限地址的临时邮箱 Bot。|  | 维护中 |

## 博客

| 名称 | 特性 |在线地址 | 状态|
| --- | --- | --- |---|
| [cloudflare-workers-blog](https://github.com/gdtool/cloudflare-workers-blog) |这是一个运行在cloudflare workers 上的博客程序,使用 cloudflare KV作为数据库,无其他依赖. 兼容静态博客的速度,以及动态博客的灵活性,方便搭建不折腾. |   <https://blog.gezhong.vip/> | 维护中|
| [cloudflare-workers-blog](https://github.com/kasuganosoras/cloudflare-worker-blog) |Cloudflare workers + Github 实现的动态博客系统，使用边缘计算，无需服务器| | 好像是不维护了|
| [microfeed](https://github.com/microfeed/microfeed) |一个在 Cloudflare 上自托管的轻量级内容管理系统 (CMS)。通过 microfeed，您可以轻松地将各种内容（例如音频、视频、照片、文档、博客文章和外部 URL）以 Web、RSS 和 JSON 的形式发布到 feed。对于想要自行托管自己的 CMS 而无需运行自己的服务器的精通技术的个人来说，这是完美的解决方案。| <https://www.microfeed.org/> | 维护中|
| [emaction.frontend](https://github.com/emaction/emaction.frontend) |基于Cloudflare D1实现的 GitHub 风格的 Reactions 点赞功能， 本项目是前端。| <https://emaction.cool/>| 维护中|
| [emaction.backend](https://github.com/emaction/emaction.backend) |基于Cloudflare D1实现的 GitHub 风格的 Reactions 点赞功能， 本项目是后端。| <https://emaction.cool/> | 维护中|
| [serverless-cloud-notepad](https://github.com/s0urcelab/serverless-cloud-notepad) |基于 Cloudflare Worker 实现的Serverless Cloud Notepad 云笔记。| <https://note.src.moe/y6y> | 维护中|


# 脚手架

| 名称 | 特性 |在线地址 | 状态|
| --- | --- | --- |---|
| [nextflare](https://github.com/ccbikai/nextflare) |Next.js App running with Lemon Squeezy on Cloudflare. |   <https://nextflare-template.pages.dev/> | 维护中|

## 短链

| 名称 | 特性 |在线地址 | 状态|
| --- | --- | --- |---|
| [short](https://github.com/igengdu/short/) |一个使用 Cloudflare Pages 创建的 URL 缩短器。| <https://d.igdu.xyz/> | 维护中|
| [short](https://github.com/x-dr/short) |一个使用 Cloudflare Pages 创建的 URL 缩短器。| <https://d.131213.xyz/> | 维护中|
| [linklet](https://github.com/harrisonwang/linklet) |一个使用 Cloudflare Pages 创建的 URL 缩短器。这个是基于API模式实现，使用场景更多一些 | <https://wss.so/> | 维护中|
| [Url-Shorten-Worker](https://github.com/crazypeace/Url-Shorten-Worker) |使用秘密路径访问操作页面。支持自定义短链。API 不公开服务。页面缓存设置过的短链。长链接文本框预搜索localStorage。增加删除某条短链的按钮。增加读取KV的按钮。变身网络记事本 Pastebin。变身图床 Image Hosting。A URL Shortener created using Cloudflare worker and KV| <https://urlsrv.crazypeace.workers.dev/bodongshouqulveweifengci> | 维护中 |
| [duanwangzhi](https://github.com/Closty/duanwangzhi) |无需服务即可缩短您的链接，因为它基于 Cloudflare 工作人员功能，具有极简风格。|  | 好像是不维护了 |
| [Url-Shorten-Worker](https://github.com/horsemail/Url-Shorten-Worker) |这个是fork的crazypeace的Url-Shorten-Worker， 使用秘密路径访问操作页面。支持自定义短链。API 不公开服务。页面缓存设置过的短链。长链接文本框预搜索localStorage。增加删除某条短链的按钮。增加读取KV的按钮。变身网络记事本 Pastebin。变身图床 Image Hosting。A URL Shortener created using Cloudflare worker and KV。| <https://1way.eu.org/bodongshouqulveweifengci> | 维护中  |
| [CloudFlare-Pages-UrlShorten](https://github.com/Jiaocz/CloudFlare-Pages-UrlShorten) |一个多功能的URL短链工具。|  | 维护中 |
| [Url-Shorten-Worker](https://github.com/Monopink/Url-Shorten-Worker/) |在原分支和 crazypeace 分支部分功能基础上优化了页面，增加了管理员用户、访客身份，增加正则表达式匹配功能，支持了环境变量配置，以及其他细节性改进。| <https://url-shortner-demo.iou.icu/> | 维护中  |
| [CloudflareWorker-KV-UrlShort](https://github.com/Ai-Yolo/CloudflareWorker-KV-UrlShort) |使用Cloudflare Worker创建的URL缩短器, 支持自定义首页, 支持Menu Short, 支持短网址、文本、网页分享 URL。|  | 维护中|
| [Sink](https://github.com/ccbikai/Sink) |ccbikai/Sink 是一个在 Cloudflare 上完全运行的简单、快速、安全的链接缩短器，具备分析功能和控制台面板.| <https://sink.cool/> | 维护中|
| [short](https://github.com/molikai-work/short) | 基于 x-dr/short 的项目修改，新增了可以设置短链密码和管理短链、使用 Turnstile 人机验证、黑名单域名管理、跳转页面配置、多域名配置使用。 | [Demo 地址](https://c1n.top/) | 维护中 |



## 网站分析

| 名称 | 特性 |在线地址 | 状态|
| --- | --- | --- |--- |
| [analytics_with_cloudflare](https://github.com/yestool/analytics_with_cloudflare) |免费开源网页访客计数器, Webviso 是一个基于Cloudflare worker服务+Cloudflare D1数据库实现的完全免费的在线web访客统计服务。 功能与目前常用的 不蒜子 - 极简网页计数器 相同。Webviso完全开源，你可以实现自定义需求。 基于Cloudflare的微服务架构可快速自行部署上线。 | <https://webviso.yestool.org/> |维护中|
| [counterscale](https://github.com/benvinegar/counterscale) |Counterscale 是一个简单的 Web 分析跟踪器和仪表板，效果和 umami 类似，您可以在 Cloudflare 上自行托管。它的设计易于部署和维护，即使在高流量的情况下，您的操作成本也应该接近于零（Cloudflare 的免费套餐假设可以支持每天高达 10 万次点击）。 | <https://counterscale.dev/> |维护中|

## 隧道

| 名称 | 特性 |在线地址 | 状态|
| --- | --- | --- |--- |
| [Cloudflared-web](https://github.com/WisdomSky/Cloudflared-web) |Cloudflared-web 是一个 docker 镜像，它打包了 cloudflared cli 和简单的 Web UI，以便轻松启动/停止 cloudflare 隧道。 |  |维护中|

## 加速

| 名称 | 特性 |在线地址 | 状态|
| --- | --- | --- |--- |
| [gh-proxy](https://github.com/hunshcn/gh-proxy) |github release、archive以及项目文件的加速项目，支持clone，有Cloudflare Workers无服务器版本以及Python版本。 | <https://gh.api.99988866.xyz/> |维护中|
| [githubbox](https://github.com/dferber90/githubbox) |在 CodeSandbox 中快速打开任何 GitHub 存储库。 |  |好像不维护了|
| [gh-proxy](https://github.com/crazypeace/gh-proxy) |github release、archive以及项目文件的加速项目. 支持 api.github.com, git.io. | <https://ghproxy.lvedong.eu.org/> |维护中|
| [cf-proxy-ex](https://github.com/1234567Yang/cf-proxy-ex) |Cloudflare超级代理，Duckduckgo代理（可用AI聊天），OpenAI/ChatGPT代理，Github加速，在线代理。Cloudflare super proxy, setting up a free proxy by using Cloudflare worker. | <https://y.demo.wvusd.homes/> |维护中|
| [cloudflare-docker-proxy](https://github.com/ciiiii/cloudflare-docker-proxy) |一个名为 cloudflare-docker-proxy 的项目，这是一个在 Cloudflare Worker 上运行的 Docker Hub 注册代理. |  |维护中|
| [CF-Workers-docker.io](https://github.com/cmliu/CF-Workers-docker.io) |这个项目是一个基于 Cloudflare Workers 的 Docker 镜像代理工具。它能够中转对 Docker 官方镜像仓库的请求，解决一些访问限制和加速访问的问题. | <https://docker.fxxk.dedyn.io/> |维护中|
| [cf-workers-proxy](https://github.com/jonssonyan/cf-workers-proxy) | Cloudflare Workers HTTP 反向代理，理论上支持代理任何被屏蔽的域名，只需要设置环境变量 PROXY_HOSTNAME 为被屏蔽的域名 |  | 维护中 |

## 文件分享

| 名称 | 特性 |在线地址 | 状态|
| --- | --- | --- |--- |
| [pastebin-worker](https://github.com/SharzyL/pastebin-worker) |介绍一个部署在 Cloudflare Workers 上的开源 Pastebin，通过URL分享"文本"或"文件"。如CF免费套餐：每天允许 10W 次读取、1000 次写入和 删除操作，大小限制在 25 MB 以下，轻量用足够了。自己部署或直接用。它还有“删除时间设置”和“密码”功能，可以设置一段时间后删除您的paste。用于twitter分享文件和文本，极好 | <https://shz.al/> |维护中|
| [FileWorker](https://github.com/yllhwa/FileWorker) |运行在Cloudflare Worker上的在线剪贴板/文件共享 |  |维护中|
| [dingding](https://github.com/iiop123/dingding) |一款基于cloudflare workers的文件传输工具，文件存储在cloudflare KV中 |  |好像不维护了|

## 测速

| 名称 | 特性 |在线地址 | 状态|
| --- | --- | --- |--- |
| [CloudflareSpeedTest](https://github.com/XIU2/CloudflareSpeedTest) |国外很多网站都在使用 Cloudflare CDN，但分配给中国内地访客的 IP 并不友好（延迟高、丢包多、速度慢）。虽然 Cloudflare 公开了所有 IP 段 ，但想要在这么多 IP 中找到适合自己的，怕是要累死，于是就有了这个软件。 | |维护中|
| [SpeedTest](https://speed.cloudflare.com/) |官方的SpeedTest工具。 | |运行中|

## 监控

| 名称 | 特性 |在线地址 | 状态|
| --- | --- | --- |--- |
| [UptimeFlare](https://github.com/lyc8503/UptimeFlare) |基于 Cloudflare Worker 的无服务器站点监控工具， 支持 HTTP/HTTPS/TCP 多种协议的端口监控， 可以从全球数百个城市发起地理位置特定的检查， 自定义的请求参数和响应校验规则,灵活适配各类监控场景。 | <https://uptimeflare.pages.dev/> |维护中|
| [cf-workers-status-page](https://github.com/eidam/cf-workers-status-page) |监控您的网站，展示状态（包括每日历史记录），并在网站状态发生变化时收到 Slack 通知。使用 Cloudflare Workers、CRON 触发器和 KV 存储。 | <https://status-page.eidam.dev/> |维护中|

# 文章

| 名称 | 特性 |在线地址 | 状态|
| --- | --- | --- |--- |
| [workers](https://igdux.com/workers) |Cloudflare Workers优秀项目收集。| |有效中|
| [accelerate-and-secure-with-cloudflared](https://nova.moe/accelerate-and-secure-with-cloudflared/) |这是一篇博客，主要是教你使用 Cloudflare Argo Tunnel(cloudflared) 来加速和保护你的网站。 |  |有效中|
| [jsonbin](https://www.owenyoung.com/blog/jsonbin/) |在 Cloudflare Workers 部署一个 JSON as a Storage 服务。| |有效中|
| [cronbin](https://www.owenyoung.com/blog/cronbin/) |在 Cloudflare Workers 部署一个带有 Dashboard 的 Cron 服务。| |有效中|
| [using-cloudflare-worker-proxy-google](https://xiaowangye.org/posts/using-cloudflare-worker-proxy-google/) |使用 Cloudflare Worker 代理 Google 站点。| |有效中|
| [Use-Cloudflare-Zero-Trust-protect-your-web-applications](https://jiapan.me/2023/Use-Cloudflare-Zero-Trust-protect-your-web-applications/) |使用 Cloudflare Zero Trust 保护你的 Web 应用。| |有效中|
| [Nextjs-app-router-with-cloudflare-r2](https://juejin.cn/post/7306723921717166131) |如何在 Next.js 13的 app/ 目录中使用 Cloudflare R2 存储。| |有效中|
| [cloudflare-webssh-zerotrust](https://josephcz.xyz/technology/network/cloudflare-webssh-zerotrust/) |使用 Cloudflare ZeroTrust 搭建 WebSSH。| |有效中|
| [免费的 CAPTCHA 替代品](https://www.cloudflare.com/zh-cn/products/turnstile/) |官方出品，免费的 CAPTCHA 替代品。| |有效中|
| [通过 Cloudflare 页面函数向 Telegram 发消息](https://liujiacai.net/blog/2024/05/07/telegram-bot-functions/) | 介绍如何利用页面函数作为 GitHub 的 Webhook 地址，将指定事件转发到 Telegram 频道中。| |有效中|
| [使用Cloudflare Workers制作博客AI摘要](https://mabbs.github.io/2024/07/03/ai-summary.html) | 介绍使用Cloudflare Workers + Workers AI + D1数据库实现博客AI摘要。| |有效中|
| [Cloudflare Workers 指定区域运行](https://blog.lyc8503.net/post/cloudflare-worker-region/) | 介绍如何强制 Workers 代码在特定节点运行。| | 有效中|

## 其他

| 名称 | 特性 |在线地址 | 状态|
| --- | --- | --- |--- |
| [silk-privacy-pass-client](https://chromewebstore.google.com/detail/silk-privacy-pass-client/ajhmfdgkijocedmfjonnpjfojldioehi) |频繁出现Cloudflare人机验证，可以用这个Cloudflare官方插件解决，装了之后，再也不会动不动跳出人机验证了。 | | 维护中|
| [WARP-Clash-API](https://github.com/vvbbnn00/WARP-Clash-API) |该项目可以让你通过订阅的方式使用WARP+，支持Clash、Shadowrocket等客户端。项目内置了 刷取WARP+流量的功能，可以让你的WARP+流量不再受限制（每18秒可获得1GB流量），同时， 配备了IP选优功能。支持Docker compose 一键部署，无需额外操作，即可享受你自己的WARP+私 有高速节点！ | |维护中|
| [ip-api](https://github.com/ccbikai/ip-api) |利用 Cloudflare Workers / Vercel Edge / Netlify Edge 快速搭一个获取 IP 地址和地理位置信息的接口。|<https://html.zone/ip> |维护中|
| [ChatGPT-Telegram-Workers](https://github.com/TBXark/ChatGPT-Telegram-Workers) |轻松在 Cloudflare Workers 上部署您自己的 Telegram ChatGPT 机器人，有详细的视频和图文教程，搭建过程也不复杂，小白也能上手。| |维护中|
| [RSSWorker](https://github.com/yllhwa/RSSWorker) |RSSWorker 是一个轻量级的 RSS 订阅工具，可以部署在 Cloudflare Worker 上。| |维护中|
| [deeplx-for-cloudflare](https://github.com/ifyour/deeplx-for-cloudflare) |Deploy DeepLX on Cloudflare。|<https://deeplx.mingming.dev/> |维护中|
| [sub_converter_convert](https://github.com/zzNeutrino/sub_converter_convert) |转换ssr/v2ray订阅链接转换的工具。| |好像不维护了|
| [telegram-counter](https://github.com/iamshaynez/telegram-counter) |用纯粹的 Cloudflare Worker 和 D1 数据库写了个 Telegram 的后端，方便可以随时随地的做一些打卡的记录……。| |好像不维护了|
| [Cloudflare-No-Tracked](https://github.com/fwqaaq/Cloudflare-No-Tracked) | 用于去除 b 站以及小红书的跟踪链接，同时也有 tg 的 bot 版本 | <https://notracked.fwqaq.us/> | 维护中 |
| [dnschecker](https://dnschecker.org/) | Cloudflare官方推荐的，检测域名解析 |  | 有效中 |
| [blockedinchina](https://www.comparitech.com/privacy-security-tools/blockedinchina/) |  Cloudflare官方推荐的，检测域名是否被墙 |  | 有效中 |
| [Serverless Cloud Notepad](https://github.com/s0urcelab/serverless-cloud-notepad) |运行在 Cloudflare 上的云记事本，搭建简单，当做临时文本中转挺方便，并且支持 Markdown 语法，支持加密。| | 好像不维护了|
| [prisma-with-cloudflare-d1](https://www.prisma.io/docs/orm/overview/databases/cloudflare-d1) |本文介绍了如何使用 Prisma 与 Cloudflare D1 数据库进行交互。首先介绍了 Prisma 的基本概念和架构，然后详细介绍了如何连接和查询 Cloudflare D1 数据库。最后，提供了一些使用 Prisma 与 Cloudflare D1 数据库的实用技巧和最佳实践。| | 有效中|
| [cohere2openai-cf-worker](https://github.com/ckt1031/cohere2openai-cf-worker) |这是一个简单的 Cloudflare Worker，可将 Cohere API 转换为 OpenAI API，可轻松部署到 Cloudflare Workers。| | 维护中|
| [cohere2openai](https://github.com/beanqi/cohere2openai) |Cloudflare Worker 将 Cohere API 转换为 OpenAI API。| | 维护中|
| [locnode](https://github.com/minlearn/locnode) |selfhost light federated community app runs on cloudflare,第一款能在cf上运行的自建轻量联合社区🚀🎉。| <https://locnode.com/> | 维护中|
| [Siri Ultra](https://github.com/fatwang2/siri-ultra) |The assistant is run on Cloudflare Workers and can work with any LLM model。|  | 维护中|
| [cobalt page function](https://github.com/jiacai2050/blog-snippets/blob/main/cloudflare/cobalt.js) | 利用页面函数调用 cobalt 接口，获取视频下载地址。| <https://liujiacai.net/api/cobalt> | 维护中|
| [CloudFlare Radar](https://radar.cloudflare.com/scan) | 看某个网站的技术栈。|  | 维护中|
| [wr.do](https://github.com/oiov/wr.do) | 基于 Cloudflare 的多租户 DNS 分发系统。开源且免费提供 DNS 解析、短链接生成。| https://wr.do  | 维护中|
| [cloudflare-proxy-sites](https://github.com/seadfeng/cloudflare-proxy-sites) | Cloudflare Workers web proxy 二级域名访问方式。 | [Demo 地址](https://www.proxysites.ai.serp.ing/) | 维护中 |
| [web-archive](https://github.com/Ray-D-Song/web-archive) | 基于 Cloudflare 的免费网页归档和分享工具。包含一个浏览器插件和运行在 Cloudflare page 上的服务 | https://github.com/Ray-D-Song/web-archive | 维护中 |





## 教程

| 名称 | 特性 |在线地址 | 状态|
| --- | --- | --- |--- |
| [cloudflare-quickstart](https://github.com/zgimszhd61/cloudflare-quickstart) |  一个快速入门指南,帮助您开始使用 Cloudflare Workers |  | 更新中 |
| [cloudflare-tunnel](https://dmesg.app/cloudflare) |  一系列关于如何使用 Cloudflare Zero Trust 创建大内网以及解决被墙服务器问题的技术博客。 |  | 更新中 |
| [cloudflare-worker-gmail-resend-enterprise-email](https://cleanclip.cc/zh/developer/cloudflare-worker-gmail-resend-enterprise-email) |  Cloudflare + Gmail + Resend 十分钟轻松拥有免费的企业邮箱。 |  | 更新中 |



## 群组

[一个群](https://t.me/indiehackertools)

## 捐赠

首先十分幸运能在Github上与你相识，其次十分感谢您对我的项目感兴趣，如果说我的项目能够对您有一些帮助，还希望您可以打赏支持一下，这将会对我有莫大的鼓励，谢谢！

![](./docs/alipay_small.jpeg)

## Contributors

<a href="https://github.com/zhuima/awesome-cloudflare/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=zhuima/awesome-cloudflare" />
</a>

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=zhuima/awesome-cloudflare&type=Timeline)](https://star-history.com/#zhuima/awesome-cloudflare&Timeline)
