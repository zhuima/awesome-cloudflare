<div align="center">
  <h1 align="center">Awesome Cloudflare <img src="https://img.shields.io/github/stars/zhuima/awesome-cloudflare?label=Stars" alt="stars"></h1>

  Dieses Repository enthält nur Open-Source-Tools, die auf Cloudflare basieren, und bietet unabhängigen Entwicklern in der frühen Erkundungsphase eine zeitsparende und sorgenfreie Tool-Sammlung, die kontinuierlich aktualisiert wird...

  [Chinesisch](./README.md) / [Englisch](./README-EN.md) / [Spanisch](./README-ES.md) / [Deutsch](./README-DE.md)
  
  ![awesome-cloudflare](./docs/awesome-cloudflare-en.svg)
</div>

# [<img src="https://img.techrk1688.eu.org/file/e44951f61086ae4dc9591.png" width="250" align="right" alt="Cloudflare">](https://www.cloudflare.com)
>
> [![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&vCenter=true&multiline=true&random=false&height=80&lines=Ausgew%C3%A4hlte+Internet+Beacon;+Cloudflare+Open-Source-Projekte%3B+Anleitungen%2C+Blogs+und+andere;+Ressourcen+aufgelistet.)](https://git.io/typing-svg)

Cloudflare, auch bekannt als der Cyber-Bodhisattva, bietet Dienste für Content Delivery Networks (CDN), DDoS-Minderung, Internetsicherheit und verteilte Domain Name Server (DNS), die zwischen den Besuchern und den Hosting-Anbietern der Cloudflare-Nutzer stehen und als Reverse-Proxy für Websites fungieren.

**Aufnahmekriterien:**

- Unterstützt, aber nicht beschränkt auf unabhängige Entwickler, um die Entwicklungseffizienz zu verbessern
- Unterstützt, aber nicht beschränkt auf unabhängige Entwickler, um Kosten zu senken
- Einfach und bequem genug

Willkommen zu PRs und Issues für Updates. Bei Problemen während der Bereitstellung oder des Betriebs können Sie ein Issue erstellen oder uns für Beratung kontaktieren.

## Weitere drei Projekte, die von Interesse sein könnten

[Technologie-Stack und Tools für unabhängige Entwickler: Erste Station für den internationalen Markt, Werkzeuge bereitstellen](https://chuhai.tools/)
[Ausgewählte Kolumnen des Zeitungsjungen: Wenn Sie eine Kolumne des Zeitungsjungen kaufen möchten, können Sie dies über diesen Link tun](https://xiaobaot.best/)
[SEO-Tool-Navigationsseite, Unterstützung für Betriebsmitarbeiter und unabhängige Entwickler](https://seo.chuhai.tools/)

## Inhaltsverzeichnis

- [Weitere drei Projekte, die von Interesse sein könnten](#weitere-drei-projekte-die-von-interesse-sein-k%C3%B6nnten)
- [Inhaltsverzeichnis](#inhaltsverzeichnis)
- [Bildhosting](#bildhosting)
- [E-Mail](#e-mail)
- [Blog](#blog)
- [Gerüst](#gerüst)
- [Kurzlink](#kurzlink)
- [Website-Analyse](#website-analyse)
- [Tunnel](#tunnel)
- [Beschleunigung](#beschleunigung)
- [Dateifreigabe](#dateifreigabe)
- [Geschwindigkeitstest](#geschwindigkeitstest)
- [Ueberwachung](#ueberwachung)
- [Artikel](#artikel)
- [Sonstiges](#sonstiges)
- [Tutorials](#tutorials)
- [Eine Gruppe wurde erstellt, wer beitreten möchte, kann dies tun](#eine-gruppe-wurde-erstellt-wer-beitreten-m%C3%B6chte-kann-dies-tun)
- [Mitwirkende](#mitwirkende)
- [Sternenhistorie](#sternenhistorie)

## Bildhosting

| Name | Merkmale | Online-Adresse | Status |
| --- | --- | --- | --- |
| [Telegraph-Image-Hosting](https://github.com/missuo/Telegraph-Image-Hosting) | Nutzt Telegraph für kostenloses Bildhosting | | Nicht mehr gewartet |
| [cf-image-hosting](https://github.com/ifyour/cf-image-hosting) | Unbegrenztes kostenloses Bildhosting auf Telegraph, gehostet auf Cloudflare. | <https://images.mingming.dev> | Wird gewartet |
| [img-mom](https://github.com/beilunyang/img-mom) | Basierend auf Cloudflare Workers, leicht und völlig kostenlos, unterstützt mehrere Bildhosting-Dienste (Telegram/Cloudflare R2/Backblaze B2, weitere in Unterstützung), schnelle Bereitstellung. Schnelle Selbstbereitstellung mit Wrangler. | | Wird gewartet |
| [workers-image-hosting](https://github.com/iiop123/workers-image-hosting) | Bildhosting basierend auf Cloudflare Workers, Daten gespeichert in KV | | Wird gewartet |
| [Telegraph-Image](https://github.com/cf-pages/Telegraph-Image) | Kostenlose Bildhosting-Lösung, Alternative zu Flickr/imgur. Nutzt Cloudflare Pages und Telegraph. | <https://im.gurl.eu.org/> | Wird gewartet |
| [cloudflare-worker-image](https://github.com/ccbikai/cloudflare-worker-image) | Bildverarbeitung mit Cloudflare Worker, abhängig von Photon, unterstützt Skalierung, Zuschneiden, Wasserzeichen, Filter und andere Funktionen. | | Wird gewartet |
| [tgState](https://github.com/csznet/tgState) | Nutzt Telegram als Speichersystem für externe Dateilinks, keine Beschränkungen für Dateigröße und -format. | <https://tgstate.vercel.app> | Wird gewartet |

## E-Mail

| Name | Merkmale | Online-Adresse | Status |
| --- | --- | --- | --- |
| [vmail](https://github.com/oiov/vmail) | 📫 Open-Source-Tool für temporäre E-Mails, unterstützt das Senden und Empfangen von E-Mails. | <https://vmail.dev/> | Wird gewartet |
| [smail](https://github.com/akazwz/smail) | Temporärer E-Mail-Dienst | <https://smail.pw/> | Wird gewartet |
| [Email.ML](https://email.ml/) | Ein temporärer E-Mail-Dienst, der im Cloudflare-Netzwerk läuft | | Nicht offen Quelle |
| [cloudflare_temp_email](https://github.com/dreamhunter2333/cloudflare_temp_email) | Erstellung temporärer E-Mails mit Cloudflare's kostenlosen Diensten | <https://temp-email.dreamhunter2333.xyz/> | Wird gewartet |
| [mail2telegram](https://github.com/TBXark/mail2telegram) | Ein Telegram Bot basierend auf Cloudflare Email Routing Worker, der E-Mails in Telegram-Nachrichten umwandelt. Ermöglicht die Erstellung eines temporären E-Mail-Bots mit unbegrenzten Adressen. | | Wird gewartet |

## Blog

| Name | Merkmale | Online-Adresse | Status |
| --- | --- | --- | --- |
| [cloudflare-workers-blog](https://github.com/gdtool/cloudflare-workers-blog) | Ein Blog-Programm, das auf Cloudflare Workers läuft, verwendet Cloudflare KV als Datenbank, keine anderen Abhängigkeiten. Kompatibel mit der Geschwindigkeit von statischen Blogs und der Flexibilität von dynamischen Blogs, einfach einzurichten. | <https://blog.gezhong.vip/> | Wird gewartet |
| [cloudflare-workers-blog](https://github.com/kasuganosoras/cloudflare-worker-blog) | Dynamisches Blog-System, implementiert mit Cloudflare Workers + Github, nutzt Edge Computing, kein Server erforderlich | | Scheint nicht gewartet zu werden |
| [microfeed](https://github.com/microfeed/microfeed) | Ein selbst gehostetes, leichtgewichtiges Content Management System (CMS) auf Cloudflare. Mit microfeed können Sie verschiedene Inhalte (wie Audio, Video, Fotos, Dokumente, Blog-Posts und externe URLs) einfach als Web, RSS und JSON veröffentlichen. Perfekt für technisch versierte Personen, die ihr eigenes CMS hosten möchten, ohne einen eigenen Server zu betreiben. | <https://www.microfeed.org/> | Wird gewartet |
| [emaction.frontend](https://github.com/emaction/emaction.frontend) | Basierend auf Cloudflare D1, GitHub-Stil Reactions Like-Funktion, dieses Projekt ist das Frontend. | <https://emaction.cool/> | Wird gewartet |
| [emaction.backend](https://github.com/emaction/emaction.backend) | Basierend auf Cloudflare D1, GitHub-Stil Reactions Like-Funktion, dieses Projekt ist das Backend. | <https://emaction.cool/> | Wird gewartet |

# Gerüst

| Name | Merkmale | Online-Adresse | Status |
| --- | --- | --- | --- |
| [nextflare](https://github.com/ccbikai/nextflare) | Next.js App, die mit Lemon Squeezy auf Cloudflare läuft. | <https://nextflare-template.pages.dev/> | Wartung |

## Tunnel

| Name | Merkmale | Online-Adresse | Status |
| --- | --- | --- | --- |
| [Cloudflared-web](https://github.com/WisdomSky/Cloudflared-web) | Cloudflared-web ist ein Docker-Image, das cloudflared CLI und eine einfache Web-UI integriert, um Cloudflare-Tunnel leicht zu starten/stoppen. | | Wird gewartet |

## Beschleunigung

| Name | Merkmale | Online-Adresse | Status |
| --- | --- | --- | --- |
| [gh-proxy](https://github.com/hunshcn/gh-proxy) | Beschleunigungsprojekt für GitHub Release, Archive und Projektdateien, unterstützt Clone. Verfügbar als serverlose Version auf Cloudflare Workers und als Python-Version. | <https://gh.api.99988866.xyz/> | Wird gewartet |
| [githubbox](https://github.com/dferber90/githubbox) | Öffnet jedes GitHub-Repository schnell in CodeSandbox. | | Scheint nicht gewartet zu werden |
| [gh-proxy](https://github.com/crazypeace/gh-proxy) |Ein Projekt zur Beschleunigung von GitHub-Versionen, Archiven und Projektdateien. Unterstützt api.github.com und git.io. | <https://ghproxy.lvedong.eu.org/> |Gepflegt|
| [cf-proxy-ex](<https://github.com/1234567Yang/cf-proxy-ex>) |Cloudflare Super-Proxy, Einrichten eines kostenlosen Proxys mit dem Cloudflare-Worker. | <https://y.demo.wvusd.homes/> |Wird gepflegt|

## Dateifreigabe

| Name | Merkmale | Online-Adresse | Status |
| --- | --- | --- | --- |
| [pastebin-worker](https://github.com/SharzyL/pastebin-worker) | Ein auf Cloudflare Workers basierender Open-Source-Pastebin, der "Text" oder "Dateien" über URL teilt. Unter dem kostenlosen Plan von CF: erlaubt 100.000 Lesevorgänge pro Tag, 1.000 Schreib- und Löschvorgänge, Größenbeschränkung unter 25 MB, leicht genug für den eigenen Gebrauch. Es hat auch eine "Löschzeit-Einstellung" und "Passwort"-Funktion, die es ermöglicht, Ihren Paste nach einer bestimmten Zeit automatisch zu löschen. Ideal für das Teilen von Dateien und Texten auf Twitter. | <https://shz.al/> | Wird gewartet |
| [FileWorker](https://github.com/yllhwa/FileWorker) | Online-Clipboard/Dateifreigabe, die auf Cloudflare Worker läuft | | Wird gewartet |
| [dingding](https://github.com/iiop123/dingding) | Ein Dateiübertragungstool, das auf Cloudflare Workers basiert, Dateien werden in Cloudflare KV gespeichert | | Scheint nicht gewartet zu werden |

## Geschwindigkeitstest

| Name | Merkmale | Online-Adresse | Status |
| --- | --- | --- | --- |
| [CloudflareSpeedTest](https://github.com/XIU2/CloudflareSpeedTest) | Viele ausländische Websites verwenden Cloudflare CDN, aber die für Besucher aus dem chinesischen Festland zugewiesenen IPs sind nicht benutzerfreundlich (hohe Latenz, viele Paketverluste, langsame Geschwindigkeit). Obwohl Cloudflare alle IP-Bereiche veröffentlicht hat, ist es mühsam, die passende IP aus so vielen herauszufinden, daher gibt es diese Software. | | Wird gewartet |
| [SpeedTest](https://speed.cloudflare.com/) | Offizielles SpeedTest-Tool. | | Läuft |

## Ueberwachung

| Name | Funktionen | Online-Adresse | Status |
| --- | --- | --- | --- |
| [UptimeFlare](https://github.com/lyc8503/UptimeFlare) | Ein serverloses Website-Überwachungstool basierend auf Cloudflare Worker. Es unterstützt die Überwachung von Ports für mehrere Protokolle, einschließlich HTTP/HTTPS/TCP. Es kann geografisch spezifische Überprüfungen aus Hunderten von Städten weltweit durchführen, mit anpassbaren Anforderungsparametern und Regeln zur Validierung der Antwort, anpassbar für verschiedene Überwachungsszenarien. | | In Wartung |
| [cf-workers-status-page](https://github.com/eidam/cf-workers-status-page) | Überwachen Sie Ihre Website, zeigen Sie den Status (einschließlich täglicher Historie) an und erhalten Sie Slack-Benachrichtigungen, wenn sich der Status der Website ändert. Verwendet Cloudflare Workers, CRON-Auslöser und KV-Speicher. | <https://status-page.eidam.dev/> | In Wartung |

## Artikel

| Name | Merkmale | Online-Adresse | Status |
| --- | --- | --- | --- |
| [workers](https://igdux.com/workers) | Sammlung von hervorragenden Projekten auf Cloudflare Workers. | | Aktiv |
| [accelerate-and-secure-with-cloudflared](https://nova.moe/accelerate-and-secure-with-cloudflared/) | Ein Blog, der hauptsächlich lehrt, wie man Cloudflare Argo Tunnel (cloudflared) verwendet, um Ihre Website zu beschleunigen und zu sichern. | | Aktiv |
| [jsonbin](https://www.owenyoung.com/blog/jsonbin/) | Bereitstellung eines JSON as a Storage Service auf Cloudflare Workers. | | Aktiv |
| [cronbin](https://www.owenyoung.com/blog/cronbin/) | Bereitstellung eines Cron-Dienstes mit Dashboard auf Cloudflare Workers. | | Aktiv |
| [using-cloudflare-worker-proxy-google](https://xiaowangye.org/posts/using-cloudflare-worker-proxy-google/) | Verwendung von Cloudflare Worker als Proxy für Google-Sites. | | Aktiv |
| [Use-Cloudflare-Zero-Trust-protect-your-web-applications](https://jiapan.me/2023/Use-Cloudflare-Zero-Trust-protect-your-web-applications/) | Verwendung von Cloudflare Zero Trust zum Schutz Ihrer Webanwendungen. | | Aktiv |
| [Nextjs-app-router-with-cloudflare-r2](https://juejin.cn/post/7306723921717166131) | Wie man Cloudflare R2 Storage im app/ Verzeichnis von Next.js 13 verwendet. | | Aktiv |
| [cloudflare-webssh-zerotrust](https://josephcz.xyz/technology/network/cloudflare-webssh-zerotrust/) | Aufbau von WebSSH mit Cloudflare ZeroTrust. | | Aktiv |
| [Kostenlose CAPTCHA-Alternative](https://www.cloudflare.com/zh-cn/products/turnstile/) | Offizielles Produkt, kostenlose CAPTCHA-Alternative. | | Aktiv |
| [Nachrichten an Telegram über Cloudflare Page Functions senden](https://liujiacai.net/blog/2024/05/07/telegram-bot-functions/) | Dieser Artikel erklärt, wie man Seitenfunktionen als GitHub-

## Sonstiges

| Name | Merkmale | Online-Adresse | Status |
| --- | --- | --- | --- |
| [silk-privacy-pass-client](https://chromewebstore.google.com/detail/silk-privacy-pass-client/ajhmfdgkijocedmfjonnpjfojldioehi) | Offizielles Cloudflare-Plugin zur Lösung häufiger CAPTCHA-Überprüfungen. Nach der Installation treten keine CAPTCHA-Überprüfungen mehr auf. | | Wird gewartet |
| [WARP-Clash-API](https://github.com/vvbbnn00/WARP-Clash-API) | Dieses Projekt ermöglicht es Ihnen, WARP+ über ein Abonnement zu nutzen, unterstützt Clients wie Clash, Shadowrocket usw. Das Projekt enthält eine Funktion zum Sammeln von WARP+ Traffic, sodass Ihr WARP+ Traffic nicht mehr begrenzt ist (jede 18 Sekunden 1GB Traffic), und es verfügt über eine IP-Optimierungsfunktion. Unterstützt Docker compose für eine einfache Ein-Klick-Bereitstellung, um Ihren eigenen WARP+ High-Speed-Knoten zu genießen! | | Wird gewartet |
| [ip-api](https://github.com/ccbikai/ip-api) | Schnelle Einrichtung einer Schnittstelle zur Abfrage von IP-Adressen und geografischen Informationen mit Cloudflare Workers / Vercel Edge / Netlify Edge. | <https://html.zone/ip> | Wird gewartet |
| [ChatGPT-Telegram-Workers](https://github.com/TBXark/ChatGPT-Telegram-Workers) | Einfache Bereitstellung Ihres eigenen Telegram ChatGPT-Bots auf Cloudflare Workers, mit detaillierten Video- und Textanleitungen, einfacher Aufbau, auch für Anfänger geeignet. | | Wird gewartet |
| [RSSWorker](https://github.com/yllhwa/RSSWorker) | RSSWorker ist ein leichtes RSS-Abonnement-Tool, das auf Cloudflare Worker bereitgestellt werden kann. | | Wird gewartet |
| [deeplx-for-cloudflare](https://github.com/ifyour/deeplx-for-cloudflare) | Bereitstellung von DeepLX auf Cloudflare. | <https://deeplx.mingming.dev/> | Wird gewartet |
| [sub_converter_convert](https://github.com/zzNeutrino/sub_converter_convert) | Tool zur Konvertierung von ssr/v2ray Abonnement-Links. | | Scheint nicht gewartet zu werden |
| [telegram-counter](https://github.com/iamshaynez/telegram-counter) | Ein Telegram-Backend, geschrieben mit reinem Cloudflare Worker und D1-Datenbank, praktisch für das Aufzeichnen von Check-ins jederzeit und überall. | | Scheint nicht gewartet zu werden |
| [Cloudflare-No-Tracked](https://github.com/fwqaaq/Cloudflare-No-Tracked) | Zum Entfernen von Tracking-Links von Bilibili und Xiaohongshu, auch verfügbar als tg bot Version | <https://notracked.fwqaq.us/> | Wird gewartet |
| [dnschecker](https://dnschecker.org/) | Von Cloudflare offiziell empfohlen, überprüft die DNS-Auflösung | | Aktiv |
| [blockedinchina](https://www.comparitech.com/privacy-security-tools/blockedinchina/) | Von Cloudflare offiziell empfohlen, überprüft, ob Domains in China blockiert sind | | Aktiv |
| [Serverless Cloud Notepad](https://github.com/s0urcelab/serverless-cloud-notepad) | Ein auf Cloudflare basierendes Cloud-Notepad, einfach einzurichten, praktisch für den temporären Texttransfer und unterstützt Markdown-Syntax und Verschlüsselung. | | Scheint nicht gewartet zu werden |
| [prisma-with-cloudflare-d1](https://www.prisma.io/docs/orm/overview/databases/cloudflare-d1) | Dieser Artikel beschreibt, wie Sie Prisma verwenden, um mit der Cloudflare D1-Datenbank zu interagieren. Zuerst werden die Grundkonzepte und die Architektur von Prisma vorgestellt, dann wird erläutert, wie Sie eine Verbindung zur Cloudflare D1-Datenbank herstellen und Abfragen durchführen. Abschließend werden einige praktische Tipps und Best Practices für die Verwendung von Prisma mit der Cloudflare D1-Datenbank bereitgestellt. | | Aktiv |
| [cohere2openai-cf-worker](https://github.com/ckt1031/cohere2openai-cf-worker) | Ein einfacher Cloudflare Worker, der die Cohere API in die OpenAI API umwandelt, kann leicht auf Cloudflare Workers bereitgestellt werden. | | Wird gewartet |
| [cohere2openai](https://github.com/beanqi/cohere2openai) | Cloudflare Worker, der die Cohere API in die OpenAI API umwandelt. | | Wird gewartet |
| [locnode](https://github.com/minlearn/locnode) | Selfhosted light federated community app läuft auf Cloudflare, die erste App dieser Art, die auf CF läuft. | <https://locnode.com/> | Wird gewartet |
| [Siri Ultra](<https://github.com/fatwang2/siri-ultra>) | Der Assistent wird auf Cloudflare Workers ausgeführt und kann mit jedem LLM-Modell arbeiten. | | Wird gewartet |

## Tutorials

| Name | Merkmale | Online-Adresse | Status |
| --- | --- | --- | --- |
| [cloudflare-quickstart](https://github.com/zgimszhd61/cloudflare-quickstart) | Ein Schnelleinstiegsführer, der Ihnen hilft, mit Cloudflare Workers zu beginnen. | | Wird aktualisiert |
| [cloudflare-tunnel](https://dmesg.app/cloudflare) | Eine Reihe von technischen Blogs darüber, wie man Cloudflare Zero Trust verwendet, um ein großes internes Netzwerk zu erstellen und Probleme mit blockierten Servern zu lösen. | | Wird aktualisiert |

## Ich habe eine Gruppe erstellt, wer beitreten möchte, kann dies tun

![](./docs/qr.png)

## Mitwirkende

<a href="https://github.com/zhuima/awesome-cloudflare/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=zhuima/awesome-cloudflare" />
</a>

## Sternenhistorie

[![Sternverlauf Diagramm](https://api.star-history.com/svg?repos=zhuima/awesome-cloudflare&type=Timeline)](https://star-history.com/#zhuima/awesome-cloudflare&Timeline)
