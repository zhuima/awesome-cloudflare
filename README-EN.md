<div align="center">

<h1 align="center">Awesome Cloudflare <img src="https://img.shields.io/github/stars/zhuima/awesome-cloudflare?label=Stars" alt="stars"></h1>

This repository only includes open source tools based on Cloudflare, to provide a time-saving toolset for independent developers in the early figuring out period, continue to organize ......

[Chinese](./README.md) / [English](./README-EN.md) / [Spanish](./README-ES.md) / [German](./README-DE.md)

![awesome-cloudflare](./docs/awesome-cloudflare-en.svg)

</div>

# [<img src="https://img.techrk1688.eu.org/file/e44951f61086ae4dc9591.png" width="250" align="right" alt="Cloudflare">](https://www.cloudflare.com)

> [![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&vCenter=true&multiline=true&random=false&height=80&lines=Selected+open+source+projects;+from+Cloudflare+guides,+blogs+and;+other+resources+listed.)](https://git.io/typing-svg)

The entity known as the Cybersattva, Cloudflare, provides content delivery network (CDN) services, DDoS mitigation, internet security, and distributed domain name server (DNS) services. It sits between the visitor and the hosting provider of the Cloudflare user, acting as a reverse proxy for the website.

**Inclusion Criteria:**

- Helps but is not limited to independent developers increase development efficiency
- Helps but is not limited to independent developers reduce costs
- Simple and convenient enough

Feel free to submit PRs and issues to update the content. If you have any questions during deployment or operation, you can raise an issue or message me privately for consultation.

## Online Version

[Awesome Cloudflare Online Navigation](https://cloudflare.chuhai.tools)

## Contents

- [](#)
  - [Online Version](#online-version)
  - [Contents](#contents)
  - [Image Hosting](#image-hosting)
  - [Email](#email)
  - [Blog](#blog)
- [Scaffolding](#scaffolding)
  - [Short Links](#short-links)
  - [Website Analysis](#website-analysis)
  - [Tunnel](#tunnel)
  - [Acceleration](#acceleration)
  - [File Sharing](#file-sharing)
  - [Speed Test](#speed-test)
  - [Monitoring](#monitoring)
  - [Articles](#articles)
  - [Others](#others)
  - [Tutorials](#tutorials)
  - [Group](#group)
  - [Contributors](#contributors)
  - [Star History](#star-history)

## Image Hosting

| Name | Features | Online Address | Status |
| --- | --- | --- |---|
| [Telegraph-Image-Hosting](https://github.com/missuo/Telegraph-Image-Hosting) |Builds free image hosting using Telegraph.| | No longer maintained |
| [cf-image-hosting](https://github.com/ifyour/cf-image-hosting) |Host images unlimitedly for free on Telegraph, deployed on Cloudflare. | <https://images.mingming.dev> | Maintaining |
| [img-mom](https://github.com/beilunyang/img-mom) |Built on Cloudflare Workers runtime, lightweight and completely free to use, supports multiple image hosting services (Telegram/Cloudflare R2/Backblaze B2, more image hosting services are being supported), quick deployment with Wrangler. | | Maintaining |
| [workers-image-hosting](https://github.com/iiop123/workers-image-hosting) |Image hosting based on Cloudflare Workers data stored in KV. | | Maintaining |
| [Telegraph-Image](https://github.com/cf-pages/Telegraph-Image) |Free image hosting solution, alternative to Flickr/imgur. Uses Cloudflare Pages and Telegraph. | <https://im.gurl.eu.org/> | Maintaining |
| [cloudflare-worker-image](https://github.com/ccbikai/cloudflare-worker-image) |Processes images using Cloudflare Worker, dependent on Photon, supports functions such as scaling, cropping, watermarking, filtering, etc. |  | Maintaining |
| [tgState](https://github.com/csznet/tgState) |File external link system using Telegram as storage, with no restrictions on file size and format. | <https://tgstate.vercel.app>  | Maintaining |
| [roim-picx](https://github.com/roimdev/roim-picx) |A free image hosting service based on CloudFlare Pages and R2. |  |Maintaining|
| [CloudFlare-ImgBed](https://github.com/MarSeventh/CloudFlare-ImgBed)  | A free image hosting service based on CloudFlare and Telegraph. This repository is based on <https://github.com/cf-pages/Telegraph-Image> and is a remake of the original project's front-end page. Open-source, clear, beautiful, smooth animations, and versatile! | <https://demo-cloudflare-imgbed.pages.dev/> | Maintaining |
| [PixR2](https://github.com/WangQueXL/PixR2) |Multi-entry image hosting and management platform based on Cloudflare Workers + R2 |   |Maintaining|

## Email

| Name | Features | Online Address | Status |
| --- | --- | --- |---|
| [vmail](https://github.com/oiov/vmail) |📫 Open source temporary email tool. Open-source temporary email tool that supports sending and receiving emails. | <https://vmail.dev/> | Maintaining |
| [smail](https://github.com/akazwz/smail) |Temporary email service.| <https://smail.pw/> | Maintaining |
| [Email.ML](https://email.ml/) |A temporary email running on the Cloudflare network.|  | Not open sourced |
| [cloudflare_temp_email](https://github.com/dreamhunter2333/cloudflare_temp_email) |Set up a temporary email using Cloudflare's free services.|  <https://temp-email.dreamhunter2333.xyz/> | Maintaining |
| [mail2telegram](https://github.com/TBXark/mail2telegram) |A Telegram Bot based on Cloudflare Email Routing Worker that converts emails to Telegram messages. You can forward emails to the Bot with any recipient prefix, and then create a Bot with an infinite number of temporary email addresses. |  | Maintaining |
| [zmail](https://github.com/zaunist/zmail) | Z-Mail - A minimalist temporary email service built on CloudFlare's pages, worker, and D1 SQL, supporting attachment reception. | <https://mail.mdzz.uk/> | Maintaining |
| [Alle](https://github.com/bestruirui/Alle) | AI-powered email aggregation client with verification code extraction and link classification. Features temporary email service. Built on Cloudflare Workers + Next.js, serverless deployment with just a domain. | | Maintaining |
| [FreeTempMail](https://github.com/PennyJoly/FreeTempMail) | A clean and minimalist permanent free temporary email service. Protects user privacy, supports i18n internationalization, use and go. Built with NuxtPro template and Cloudflare. | <https://mail.aitre.cc> | Maintaining |

## Blog

| Name | Features | Online Address | Status |
| --- | --- | --- |---|
| [cloudflare-workers-blog](https://github.com/gdtool/cloudflare-workers-blog) |A blog program running on Cloudflare Workers, using Cloudflare KV as the database, with no other dependencies. Compatible with the speed of static blogs and the flexibility of dynamic blogs, easy to build without fuss. |   <https://blog.gezhong.vip/> | Maintaining |
| [cloudflare-workers-blog](https://github.com/kasuganosoras/cloudflare-worker-blog) |Dynamic blog system implemented with Cloudflare workers + Github, using edge computing, no need for servers. | | Seems to be not maintained |
| [microfeed](https://github.com/microfeed/microfeed) |A lightweight Content Management System (CMS) self-hosted on Cloudflare. With microfeed, you can easily publish various content (such as audio, video, photos, documents, blog posts, and external URLs) in Web, RSS, and JSON formats to feeds. Perfect solution for individuals who want to self-host their CMS without running their own server. | <https://www.microfeed.org/> | Maintaining |
| [emaction.frontend](https://github.com/emaction/emaction.frontend) |GitHub-style Reactions liking feature implemented based on Cloudflare D1, this project is the frontend. | <https://emaction.cool/>| Maintaining |
| [emaction.backend](https://github.com/emaction/emaction.backend) |GitHub-style Reactions liking feature implemented based on Cloudflare D1, this project is the backend. | <https://emaction.cool/> | Maintaining |
| [Gins-Blog](https://github.com/IchimaruGin728/Gins-Blog) | A high-performance, Agentic-First blog platform. Built on Cloudflare ecosystem. Supports MCP and Zero-Touch Deployment via OpenClaw. | <https://blog.ichimarugin728.com> | Maintaining |

# Scaffolding

| Name | Features | Online Address | Status |
| --- | --- | --- | --- |
| [nextflare](https://github.com/ccbikai/nextflare) | Next.js App running with Lemon Squeezy on Cloudflare. | <https://nextflare-template.pages.dev/> | Maintenance |

## Short Links

| Name | Features | Online Address | Status |
| --- | --- | --- |---|
| [short](https://github.com/igengdu/short/) |A URL shortener created using Cloudflare Pages. | <https://d.igdu.xyz/> | Maintaining |
| [short](https://github.com/x-dr/short) |A URL shortener created using Cloudflare Pages. | <https://d.131213.xyz/> | Maintaining |
| [linklet](https://github.com/harrisonwang/linklet) |A URL shortener created using Cloudflare Pages. This is implemented based on API mode, with more usage scenarios. | <https://wss.so/> | Maintaining |
| [Url-Shorten-Worker](https://github.com/crazypeace/Url-Shorten-Worker) |Access the operation page using a secret path. Supports custom short links. API not publicly available. Cache pages with set short links. Long link text box pre-searches localStorage. Add a button to delete a short link. Add a button to read KV. Transform into a network notepad Pastebin. Transform into an image bed Image Hosting. A URL Shortener created using Cloudflare worker and KV. | <https://urlsrv.crazypeace.workers.dev/bodongshouqulveweifengci> | Maintaining |
| [duanwangzhi](https://github.com/Closty/duanwangzhi) |Shorten your links without services, as it is based on Cloudflare Workers with minimalist style. |  | Seems to be not maintained |
| [Url-Shorten-Worker](https://github.com/horsemail/Url-Shorten-Worker) |This is a fork of crazypeace's Url-Shorten-Worker. Access the operation page using a secret path. Supports custom short links. API not publicly available. Cache pages with set short links. Long link text box pre-searches localStorage. Add a button to delete a short link. Add a button to read KV. Transform into a network notepad Pastebin. Transform into an image bed Image Hosting. A URL Shortener created using Cloudflare worker and KV. | <https://1way.eu.org/bodongshouqulveweifengci> | Maintaining |
| [CloudFlare-Pages-UrlShorten](https://github.com/Jiaocz/CloudFlare-Pages-UrlShorten) |A multifunctional URL shortening tool. |  | Maintaining |
| [Url-Shorten-Worker](https://github.com/Monopink/Url-Shorten-Worker/) |Optimized the page based on the original branch and crazypeace branch, added administrator user, visitor identity, added regular expression matching function, supported environment variable configuration, and other detailed improvements. | <https://url-shortener-demo.jhw.li/> | Maintaining  |
| [CloudflareWorker-KV-UrlShort](https://github.com/Ai-Yolo/CloudflareWorker-KV-UrlShort) |A URL shortener created using Cloudflare Worker, supports custom homepage, Menu Short, supports short URLs, text, web page sharing URL. |  | Maintaining|
| [Sink](https://github.com/ccbikai/Sink) |A Simple / Speedy / Secrue Link Shortener with Analytics, 100% run on Cloudflare.| <https://sink.cool/> |  Maintaining|
| [short](https://github.com/molikai-work/short) | A project modified based on x-dr/short, adding features like setting short link passwords, managing short links, using Turnstile CAPTCHA, managing blacklisted domains, configuring redirect pages, and using multiple domain names. | [Demo](https://c1n.top/) | Maintained |


## Website Analysis

| Name | Features | Online Address | Status |
| --- | --- | --- |--- |
| [analytics_with_cloudflare](https://github.com/yestool/analytics_with_cloudflare) |A free and open-source web visitor counter, Webviso is a completely free online web visitor statistics service based on Cloudflare Worker service + Cloudflare D1 database. Its functionality is similar to the minimalist web page counter Not Baidu - Webviso is completely open source, and you can implement custom requirements. Based on Cloudflare's microservices architecture, it can be quickly deployed and launched. | <https://webviso.yestool.org/> | Maintaining |
| [counterscale](https://github.com/benvinegar/counterscale) |Counterscale is a simple web analytics tracker and dashboard, similar to Umami, that you can self-host on Cloudflare. Its design is easy to deploy and maintain, and even with high traffic, your operating costs should be close to zero (assuming Cloudflare's free plan can handle up to 100,000 clicks per day). | <https://counterscale.dev/> | Maintaining |

## Tunnel

| Name | Features | Online Address | Status |
| --- | --- | --- |--- |
| [Cloudflared-web](https://github.com/WisdomSky/Cloudflared-web) |Cloudflared-web is a Docker image that bundles the Cloudflared CLI and a simple web UI for easily starting/stopping Cloudflare tunnels. |  | Maintaining |

## Acceleration

| Name | Features | Online Address | Status |
| --- | --- | --- |--- |
| [gh-proxy](https://github.com/hunshcn/gh-proxy) |An acceleration project for GitHub releases, archives, and project files, supporting cloning. It has a Cloudflare Workers serverless version as well as a Python version. | <https://gh.api.99988866.xyz/> | Maintaining |
| [githubbox](https://github.com/dferber90/githubbox) |Quickly open any GitHub repository in CodeSandbox. |  | Seems unmaintained |
| [gh-proxy](https://github.com/crazypeace/gh-proxy) |A project for accelerating GitHub releases, archives, and project files. Supports api.github.com and git.io. | <https://ghproxy.lvedong.eu.org/> |Maintained|
| [cf-proxy-ex](https://github.com/1234567Yang/cf-proxy-ex) |Cloudflare super proxy, setting up a free proxy by using Cloudflare worker. | <https://y.demo.wvusd.homes/> |Maintained|
| [cloudflare-docker-proxy](https://github.com/ciiiii/cloudflare-docker-proxy) | A project named cloudflare-docker-proxy, which is a Docker Hub registry proxy running on Cloudflare Worker. |  | Maintaining |
| [CF-Workers-docker.io](https://github.com/cmliu/CF-Workers-docker.io) | This project is a Docker image proxy tool based on Cloudflare Workers. It can relay requests to the official Docker image repository, solving access restrictions and accelerating access. | <https://docker.fxxk.dedyn.io/> | Maintaining |
| [cf-workers-proxy](https://github.com/jonssonyan/cf-workers-proxy) | Cloudflare Workers HTTP reverse proxy, theoretically supports proxying any blocked domain name, just set the environment variable PROXY_HOSTNAME to the blocked domain name |  | Maintaining |
| [gemini-balance-do](https://github.com/zaunist/gemini-balance-do) | Based on Cloudflare Worker and Durable Objects, this project implements a Gemini API relay (multi-key load balancing) for stable US IP access to Gemini. | https://github.com/zaunist/gemini-balance-do | Maintained |

## File Sharing

| Name | Features | Online Address | Status |
| --- | --- | --- |--- |
| [pastebin-worker](https://github.com/SharzyL/pastebin-worker) |Introduces an open-source Pastebin deployed on Cloudflare Workers, allowing sharing of "text" or "files" via URL. For CF's free tier: allows 100k reads, 1000 writes, and deletes per day, with a size limit of under 25 MB, sufficient for lightweight use. Can be self-hosted or used directly. It also features "deletion time settings" and "password" functionality, allowing you to set a time for your paste to be deleted. Great for sharing files and text on Twitter. | <https://shz.al/> | Maintaining |
| [FileWorker](https://github.com/yllhwa/FileWorker) |An online clipboard/file sharing service running on Cloudflare Worker. |  | Maintaining |
| [CloudPaste](https://github.com/ling-drag0n/CloudPaste) | A Cloudflare-based online text/large file sharing platform supporting multiple syntax Markdown rendering, self-destruct after reading, multi-storage aggregation (S3/WebDav/TG/OneDrive), password protection, and more. Can be mounted as WebDav and supports Docker deployment. | <https://doc.cloudpaste.qzz.io/> | Maintenance |
| [dingding](https://github.com/iiop123/dingding) |A file transfer tool based on Cloudflare Workers, storing files in Cloudflare KV. |  | Seems unmaintained |

## Speed Test

| Name | Features | Online Address | Status |
| --- | --- | --- |--- |
| [CloudflareSpeedTest](https://github.com/XIU2/CloudflareSpeedTest) |Many foreign websites use Cloudflare CDN, but the IPs allocated to visitors from mainland China are not friendly (high latency, packet loss, slow speed). Although Cloudflare has publicly released all IP ranges, it's daunting to find the right one among so many IPs, so this software was created. | | Maintaining |
| [SpeedTest](https://speed.cloudflare.com/) |Official SpeedTest tool. | | Active |
| [ip-check](https://github.com/lovegitgit/ip-check) |A Python-based Cloudflare CDN speed testing tool that supports multiple ways of inputting IPs (text files, IPv4/IPv6, ports, preferred domains, etc.), customizable ports, IP geolocation filtering, and IP organization name filtering. | | Maintaining |

## Monitoring

| Name | Features | Online Address | Status |
| --- | --- | --- | --- |
| [UptimeFlare](https://github.com/lyc8503/UptimeFlare) | A serverless website monitoring tool based on Cloudflare Worker. It supports monitoring ports for multiple protocols including HTTP/HTTPS/TCP. It can initiate geographically specific checks from hundreds of cities worldwide, with customizable request parameters and response validation rules, adaptable for various monitoring scenarios. | <https://uptimeflare.pages.dev/> | Under maintenance |
| [cf-workers-status-page](https://github.com/eidam/cf-workers-status-page) | Monitor your website, display status (including daily history), and receive Slack notifications when the website status changes. Utilizes Cloudflare Workers, CRON triggers, and KV storage. | <https://status-page.eidam.dev/> | Under maintenance |
| [xugou](https://github.com/zaunist/xugou)| A website monitoring and server monitoring tool based on CloudFlare. | https://xugou.mdzz.uk/ |  Under maintenance |
| [deploy-mcp](https://github.com/alexpota/deploy-mcp) | Universal deployment tracker for AI assistants with live status badges and deployment monitoring, including Cloudflare Pages support. | https://deploy-mcp.io | Active |

## Articles

| Name | Features | Online Address | Status |
| --- | --- | --- |--- |
| [workers](https://igdux.com/workers) |Collection of excellent projects using Cloudflare Workers. | | Active |
| [accelerate-and-secure-with-cloudflared](https://nova.moe/accelerate-and-secure-with-cloudflared/) |This is a blog post mainly teaching you how to use Cloudflare Argo Tunnel (cloudflared) to accelerate and protect your website. |  | Active |
| [jsonbin](https://www.owenyoung.com/blog/jsonbin/) |Deploy a JSON as a Storage service on Cloudflare Workers. | | Active |
| [cronbin](https://www.owenyoung.com/blog/cronbin/) |Deploy a Cron service with a Dashboard on Cloudflare Workers. | | Active |
| [using-cloudflare-worker-proxy-google](https://xiaowangye.org/posts/using-cloudflare-worker-proxy-google/) |Proxy Google sites using Cloudflare Worker. | | Active |
| [Use-Cloudflare-Zero-Trust-protect-your-web-applications](https://jiapan.me/2023/Use-Cloudflare-Zero-Trust-protect-your-web-applications/) |Protect your web applications with Cloudflare Zero Trust. | | Active |
| [Nextjs-app-router-with-cloudflare-r2](https://juejin.cn/post/7306723921717166131) |How to use Cloudflare R2 storage in the app/ directory of Next.js 13. | | Active |
| [cloudflare-webssh-zerotrust](https://josephcz.xyz/technology/network/cloudflare-webssh-zerotrust/) |Build WebSSH with Cloudflare ZeroTrust. | | Active |
| [Free CAPTCHA Alternative](https://www.cloudflare.com/zh-cn/products/turnstile/) |Officially produced, free CAPTCHA alternative. | | Active |
| [Sending Messages to Telegram via Cloudflare Page Functions](https://liujiacai.net/blog/2024/05/07/telegram-bot-functions/) | This article introduces how to utilize page functions as GitHub webhook addresses to forward specific events to Telegram channels. | | Active |
| [Using Cloudflare Workers to create AI blog summaries](https://mabbs.github.io/2024/07/03/ai-summary.html) | Introduce the implementation of blog AI summarization using Cloudflare Workers + Workers AI + D1 database.| | Active |
| [Build an RSS Subscription Push System with Cloudflare Worker, Hono, and Telegram Bot API](https://calpa.me/blog/build-rss-subscription-push-system-with-cloudflare-worker-hono-telegram-bot-api/) | A detailed guide on using Cloudflare Worker, Hono framework, and Telegram Bot API to build a serverless system that monitors RSS feeds and pushes updates to Telegram channels. Fully serverless, suitable for individual developers and small teams, supports scheduled tasks and duplicate message prevention. | |Active|

## Others

| Name | Features | Online Address | Status |
| --- | --- | --- | --- |
| [silk-privacy-pass-client](https://chromewebstore.google.com/detail/silk-privacy-pass-client/ajhmfdgkijocedmfjonnpjfojldioehi) |Frequent appearance of Cloudflare human verification, you can use this official Cloudflare plugin to solve it, after installation, you will no longer encounter human verification prompts. | | Under maintenance |
| [WARP-Clash-API](https://github.com/vvbbnn00/WARP-Clash-API) |This project allows you to use WARP+ through subscription, supporting clients such as Clash and Shadowrocket. The project has built-in functions to obtain WARP+ traffic, allowing you to bypass restrictions on your WARP+ traffic (1GB traffic every 18 seconds), and equipped with IP optimization function. It supports one-click deployment with Docker compose, so you can enjoy your own WARP+ private high-speed node without extra operations! | | Under maintenance |
| [ip-api](https://github.com/ccbikai/ip-api) |Set up a quick IP address and geographical location information acquisition interface using Cloudflare Workers / Vercel Edge / Netlify Edge. |<https://html.zone/ip> | Under maintenance |
| [ChatGPT-Telegram-Workers](https://github.com/TBXark/ChatGPT-Telegram-Workers) |Easily deploy your own Telegram ChatGPT bot on Cloudflare Workers, with detailed video and graphic tutorials, and an easy setup process even for beginners. | | Under maintenance |
| [RSSWorker](https://github.com/yllhwa/RSSWorker) |RSSWorker is a lightweight RSS subscription tool that can be deployed on Cloudflare Workers. | | Under maintenance |
| [deeplx-for-cloudflare](https://github.com/ifyour/deeplx-for-cloudflare) |Deploy DeepLX on Cloudflare. |<https://deeplx.mingming.dev/> | Under maintenance |
| [sub_converter_convert](https://github.com/zzNeutrino/sub_converter_convert) |Tool to convert ssr/v2ray subscription links. | | Seems to be no longer maintained |
| [telegram-counter](https://github.com/iamshaynez/telegram-counter) |A Telegram backend written purely with Cloudflare Worker and D1 database, making it convenient to make some check-in records anytime and anywhere... | | Seems to be no longer maintained |
| [Cloudflare-No-Tracked](https://github.com/fwqaaq/Cloudflare-No-Tracked) |A bot version used to remove tracking links from Bilibili and Xiaohongshu, and also has a TG bot version. | <https://notracked.fwqaq.us/> | Under maintenance |
| [dnschecker](https://dnschecker.org/) |A domain name resolution checking tool recommended by Cloudflare. |  | Active |
| [blockedinchina](https://www.comparitech.com/privacy-security-tools/blockedinchina/) |A tool recommended by Cloudflare to check if a domain name is blocked. |  | Active |
| [Serverless Cloud Notepad](https://github.com/s0urcelab/serverless-cloud-notepad) |A cloud notepad running on Cloudflare, easy to set up, convenient as a temporary text transfer, and supports Markdown syntax and encryption. | | Seems to be no longer maintained |
| [prisma-with-cloudflare-d1](https://www.prisma.io/docs/orm/overview/databases/cloudflare-d1) |This article introduces how to interact with Prisma and Cloudflare D1 database. First, it introduces the basic concepts and architecture of Prisma, and then explains in detail how to connect to and query the Cloudflare D1 database. Finally, it provides some practical tips and best practices for using Prisma with Cloudflare D1 database. | | Active |
| [cohere2openai-cf-worker](https://github.com/ckt1031/cohere2openai-cf-worker) |This is a simple Cloudflare Worker that converts Cohere API to OpenAI API, and can be easily deployed to Cloudflare Workers. | | Under maintenance |
| [cohere2openai](https://github.com/beanqi/cohere2openai) |Cloudflare Worker that converts Cohere API to OpenAI API. | | Under maintenance |
| [locnode](https://github.com/minlearn/locnode) |selfhost light federated community app runs on cloudflare。| <https://locnode.com/> | Under maintenance|
| [Siri Ultra](https://github.com/fatwang2/siri-ultra) |The assistant is run on Cloudflare Workers and can work with any LLM model。|  | Under maintenance|
| [GitPush](https://github.com/fatwang2/gitpush) |A GitHub project update subscription tool built on Cloudflare Workflow, Workers AI and Email Routing. You can subscribe to GitHub projects you follow, and receive email notifications with AI-summarized update content.| | Under maintenance|
| [CloudFlare Radar](https://radar.cloudflare.com/scan) | Check a website's technology stack. || Under maintenance |
| [wr.do](https://github.com/oiov/wr.do) | A multi-tenant DNS distribution system based on Cloudflare. Open-source and freely provides DNS resolution and short link generation. |https://wr.do | Under maintenance|
| [cloudflare-proxy-sites](https://github.com/seadfeng/cloudflare-proxy-sites) | A Cloudflare Workers web proxy with subdomain access method. | [Demo](https://www.proxysites.ai.serp.ing/) | Under maintenance|
| [web-archive](https://github.com/Ray-D-Song/web-archive) | A free web archiving and sharing tool based on Cloudflare. It includes a browser plugin and a service running on Cloudflare pages. | https://github.com/Ray-D-Song/web-archive | Updating |
| [melody-auth](https://github.com/ValueMelody/melody-auth) | An oauth and authentication system based on Cloudflare workers, D1 and KV. | <https://auth.valuemelody.com/> | Active |
| [Cloudflare-KV-Manager](https://github.com/som3canadian/Cloudflare-KV-Manager) | The missing tool for your Cloudflare KV. A more complete and simple solution for managing Cloudflare KV storage. Include a web interface and a small python lib. | <https://kv-demo.somecanadian.com> | Active |
| [CF-TOOLS](https://github.com/MainPoser/cf-tools) | Integrate commonly used development tools, AI assistants, etc. | <https://cf-tools.tianyao.qzz.io/> | Updating |
| [subpool-worker](https://github.com/illusionlie/subpool-worker) | Lightweight subscription pool service for managing and distributing proxy subscription links. | | Actively Maintained |
| [AWS-AccessBridge](https://github.com/Rexezuge-CloudflareWorkers/AWS-AccessBridge) | AWS multi-accounts management and login |  | Actively Maintained |
| [Cloudflare-Clist](https://github.com/ooyyh/Cloudflare-Clist) | An alist-like aggregated storage management service based on Cloudflare Workers | <https://down.ohyraw.qzz.io> | Actively Maintained |
| [sync-your-cookie](https://github.com/jackluson/sync-your-cookie) | Browser extension for syncing cookies to Cloudflare KV or GitHub Gist. Supports LocalStorage, Auto Merge and Auto Push rules for different sites, protobuf encoded transmission, and management panel. | | Maintaining |
| [myip](https://github.com/hoa-js/examples/tree/master/myip) | IP information detection website based on Cloudflare Workers. Supports one-click deployment, built on hoajs. | <https://myip.hoa-js.com/> | Maintaining |
| [2fa](https://github.com/hoa-js/examples/blob/master/2fa/index.js) | 2FA generation website based on Cloudflare Workers. Supports one-click deployment, built on hoajs. | <https://2fa.hoa-js.com/> | Maintaining |
| [tempnote](https://github.com/hoa-js/examples/blob/master/tempnote/tempnote.js) | Temporary note website based on Cloudflare Workers & KV. Randomly generates note addresses, responsive design, supports custom note addresses, one-click deployment, built on hoajs. | <https://tempnote.hoa-js.com/> | Maintaining |
| [CloudNav-](https://github.com/sese972010/CloudNav-) | Navigation that can be hosted on Cloudflare, with Chrome plugin for one-click bookmarking to navigation. Lightweight navigation focused on practicality. | | Maintaining |
| [memos-worker](https://github.com/souvenp/memos-worker) | Note and knowledge base powered by Cloudflare. Full Markdown support, file attachments, public sharing, Telegram integration, powerful organization, knowledge base, highly customizable, extreme performance and low cost, data sovereignty. | | Maintaining |
| [whisper_cloudflare](https://github.com/thun888/whisper_cloudflare) | Online audio transcription tool based on Whisper model, deployed on Cloudflare. Converts audio files to text and supports SRT subtitle generation. | | Maintaining |
| [micro-notepad](https://github.com/thun888/micro-notepad/) | Mini notepad, Cloudflare Worker implementation of [pereorga/minimalist-web-notepad](https://github.com/pereorga/minimalist-web-notepad). | | Maintaining |
| [cf-page-publish-mcp](https://github.com/Actrue/cf-page-publish-mcp) | Cloudflare page publishing mcp tool that can publish HTML pages to Cloudflare Workers. Can connect to AI via MCP. | | Maintaining |


## Tutorials

| Name | Features | Online Address | Status |
| --- | --- | --- | --- |
| [cloudflare-quickstart](https://github.com/zgimszhd61/cloudflare-quickstart) | A quick start guide to help you get started with Cloudflare Workers |  | Updating |
| [cloudflare-tunnel](https://dmesg.app/cloudflare) | A series of technical blogs on using Cloudflare Zero Trust to create large intranets and solve issues with blocked servers. | | Updating |
| [cloudflare-worker-gmail-resend-enterprise-email](https://cleanclip.cc/zh/developer/cloudflare-worker-gmail-resend-enterprise-email) | Cloudflare + Gmail + Resend: Get a Free Enterprise Email in Ten Minutes with Ease. |  | Updating |

## Group

[A Group](https://t.me/indiehackertools)

## Contributors

<a href="https://github.com/zhuima/awesome-cloudflare/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=zhuima/awesome-cloudflare" />
</a>

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=zhuima/awesome-cloudflare&type=Timeline)](https://star-history.com/#zhuima/awesome-cloudflare&Timeline)
