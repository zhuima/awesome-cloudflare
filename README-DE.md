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

## Online-Version

[Großartige Cloudflare-Online-Navigation](https://cloudflare.chuhai.tools)

## Inhaltsverzeichnis

- [](#)
  - [Online-Version](#online-version)
  - [Inhaltsverzeichnis](#inhaltsverzeichnis)
  - [Bildhosting](#bildhosting)
  - [E-Mail](#e-mail)
  - [Blog](#blog)
- [Gerüst](#gerüst)
  - [Tunnel](#tunnel)
  - [Beschleunigung](#beschleunigung)
  - [Dateifreigabe](#dateifreigabe)
  - [Geschwindigkeitstest](#geschwindigkeitstest)
  - [Ueberwachung](#ueberwachung)
  - [Artikel](#artikel)
  - [Sonstiges](#sonstiges)
  - [Tutorials](#tutorials)
  - [Gruppe](#gruppe)
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
| [roim-picx](https://github.com/roimdev/roim-picx) |Ein kostenloses Bildbett basierend auf CloudFlare Pages und R2. |  |Wird gewartet|
| [CloudFlare-ImgBed](https://github.com/MarSeventh/CloudFlare-ImgBed)  | Ein kostenloser Bildhosting-Dienst basierend auf CloudFlare und Telegraph. Dieses Repository basiert auf <https://github.com/cf-pages/Telegraph-Image> und ist eine Neuauflage der ursprünglichen Front-End-Seite des Projekts. Open-Source, klar, schön, geschmeidige Animationen und vielseitig! | <https://demo-cloudflare-imgbed.pages.dev/> | In Wartung |
| [PixR2](https://github.com/WangQueXL/PixR2) | Mehrfacheinstiegs-Bildhost- und Verwaltungsplattform basierend auf Cloudflare Workers + R2 |   | Wird gewartet |

## E-Mail

| Name | Merkmale | Online-Adresse | Status |
| --- | --- | --- | --- |
| [vmail](https://github.com/oiov/vmail) | 📫 Open-Source-Tool für temporäre E-Mails, unterstützt das Senden und Empfangen von E-Mails. | <https://vmail.dev/> | Wird gewartet |
| [smail](https://github.com/akazwz/smail) | Temporärer E-Mail-Dienst | <https://smail.pw/> | Wird gewartet |
| [Email.ML](https://email.ml/) | Ein temporärer E-Mail-Dienst, der im Cloudflare-Netzwerk läuft | | Nicht offen Quelle |
| [cloudflare_temp_email](https://github.com/dreamhunter2333/cloudflare_temp_email) | Erstellung temporärer E-Mails mit Cloudflare's kostenlosen Diensten | <https://temp-email.dreamhunter2333.xyz/> | Wird gewartet |
| [mail2telegram](https://github.com/TBXark/mail2telegram) | Ein Telegram Bot basierend auf Cloudflare Email Routing Worker, der E-Mails in Telegram-Nachrichten umwandelt. Ermöglicht die Erstellung eines temporären E-Mail-Bots mit unbegrenzten Adressen. | | Wird gewartet |
| [zmail](https://github.com/zaunist/zmail) | Z-Mail - Ein minimalistischer temporärer E-Mail-Dienst, der auf CloudFlare-Seiten, Worker und D1 SQL basiert und den Empfang von Anhängen unterstützt. | <https://mail.mdzz.uk/> | Wird gewartet |
| [Alle](https://github.com/bestruirui/Alle) | KI-gesteuerter E-Mail-Aggregations-Client mit Verifizierungscode-Extraktion und Link-Klassifizierung. Bietet temporären E-Mail-Dienst. Basierend auf Cloudflare Workers + Next.js, serverlose Bereitstellung mit nur einer Domain. | | Wird gewartet |
| [FreeTempMail](https://github.com/PennyJoly/FreeTempMail) | Ein sauberer und minimalistischer permanenter kostenloser temporärer E-Mail-Dienst. Schützt Benutzerdaten, unterstützt i18n-Internationalisierung, sofort einsatzbereit. Mit NuxtPro-Template und Cloudflare entwickelt. | <https://mail.aitre.cc> | Wird gewartet |

## Blog

| Name | Merkmale | Online-Adresse | Status |
| --- | --- | --- | --- |
| [cloudflare-workers-blog](https://github.com/gdtool/cloudflare-workers-blog) | Ein Blog-Programm, das auf Cloudflare Workers läuft, verwendet Cloudflare KV als Datenbank, keine anderen Abhängigkeiten. Kompatibel mit der Geschwindigkeit von statischen Blogs und der Flexibilität von dynamischen Blogs, einfach einzurichten. | <https://blog.gezhong.vip/> | Wird gewartet |
| [cloudflare-workers-blog](https://github.com/kasuganosoras/cloudflare-worker-blog) | Dynamisches Blog-System, implementiert mit Cloudflare Workers + Github, nutzt Edge Computing, kein Server erforderlich | | Scheint nicht gewartet zu werden |
| [microfeed](https://github.com/microfeed/microfeed) | Ein selbst gehostetes, leichtgewichtiges Content Management System (CMS) auf Cloudflare. Mit microfeed können Sie verschiedene Inhalte (wie Audio, Video, Fotos, Dokumente, Blog-Posts und externe URLs) einfach als Web, RSS und JSON veröffentlichen. Perfekt für technisch versierte Personen, die ihr eigenes CMS hosten möchten, ohne einen eigenen Server zu betreiben. | <https://www.microfeed.org/> | Wird gewartet |
| [emaction.frontend](https://github.com/emaction/emaction.frontend) | Basierend auf Cloudflare D1, GitHub-Stil Reactions Like-Funktion, dieses Projekt ist das Frontend. | <https://emaction.cool/> | Wird gewartet |
| [emaction.backend](https://github.com/emaction/emaction.backend) | Basierend auf Cloudflare D1, GitHub-Stil Reactions Like-Funktion, dieses Projekt ist das Backend. | <https://emaction.cool/> | Wird gewartet |
| [Gins-Blog](https://github.com/IchimaruGin728/Gins-Blog) | Eine leistungsstarke, Agentic-First-Blog-Plattform im Cloudflare-Ökosystem. Unterstützt MCP und Zero-Touch-Deployment über OpenClaw. | <https://blog.ichimarugin728.com> | Wird gewartet |

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
| [cloudflare-docker-proxy](https://github.com/ciiiii/cloudflare-docker-proxy) | Ein Projekt namens cloudflare-docker-proxy, das ein Docker Hub-Registry-Proxy ist, das auf Cloudflare Worker läuft. |  | In Wartung |
| [CF-Workers-docker.io](https://github.com/cmliu/CF-Workers-docker.io) | Dieses Projekt ist ein auf Cloudflare Workers basierendes Docker-Image-Proxy-Tool. Es kann Anfragen an das offizielle Docker-Image-Repository weiterleiten, Zugriffsrestriktionen lösen und den Zugriff beschleunigen. | <https://docker.fxxk.dedyn.io/> | In Wartung |
| [cf-workers-proxy](https://github.com/jonssonyan/cf-workers-proxy) | Der HTTP-Reverse-Proxy von Cloudflare Workers unterstützt theoretisch das Proxying aller blockierten Domänennamen. Sie müssen lediglich die Umgebungsvariable PROXY_HOSTNAME auf den blockierten Domänennamen setzen. |  | In Wartung |
| [gemini-balance-do](https://github.com/zaunist/gemini-balance-do) | Basierend auf Cloudflare Worker und Durable Objects implementiert dieses Projekt ein Gemini-API-Relay (Multi-Key-Lastenausgleich) für stabilen US-IP-Zugriff auf Gemini. | https://github.com/zaunist/gemini-balance-do | Wird gewartet |

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
| [ip-check](https://github.com/lovegitgit/ip-check) | Ein Python-basiertes Cloudflare-CDN-Geschwindigkeitstest-Tool, das mehrere Arten der IP-Eingabe unterstützt (Textdateien, IPv4/IPv6, Ports, bevorzugte Domains usw.), benutzerdefinierte Ports sowie Filterung nach IP-Standort und IP-Organisationsname. | | Wird gewartet |

## Ueberwachung

| Name | Funktionen | Online-Adresse | Status |
| --- | --- | --- | --- |
| [UptimeFlare](https://github.com/lyc8503/UptimeFlare) | Ein serverloses Website-Überwachungstool basierend auf Cloudflare Worker. Es unterstützt die Überwachung von Ports für mehrere Protokolle, einschließlich HTTP/HTTPS/TCP. Es kann geografisch spezifische Überprüfungen aus Hunderten von Städten weltweit durchführen, mit anpassbaren Anforderungsparametern und Regeln zur Validierung der Antwort, anpassbar für verschiedene Überwachungsszenarien. | <https://uptimeflare.pages.dev/>| In Wartung |
| [cf-workers-status-page](https://github.com/eidam/cf-workers-status-page) | Überwachen Sie Ihre Website, zeigen Sie den Status (einschließlich täglicher Historie) an und erhalten Sie Slack-Benachrichtigungen, wenn sich der Status der Website ändert. Verwendet Cloudflare Workers, CRON-Auslöser und KV-Speicher. | <https://status-page.eidam.dev/> | In Wartung |
| [xugou](https://github.com/zaunist/xugou)| Ein auf CloudFlare basierendes Website- und Server-Überwachungstool. | https://xugou.mdzz.uk/ | In Wartung |
| [deploy-mcp](https://github.com/alexpota/deploy-mcp) | Universeller Deployment-Tracker für KI-Assistenten mit Live-Status-Badges und Deployment-Überwachung, einschließlich Cloudflare Pages-Unterstützung. | https://deploy-mcp.io | Aktiv |

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
| [Nachrichten an Telegram über Cloudflare Page Functions senden](https://liujiacai.net/blog/2024/05/07/telegram-bot-functions/) | Dieser Artikel erklärt, wie man Seitenfunktionen als GitHub- | | Aktiv |
| [Erstellen einer Blog-AI-Zusammenfassung mit Cloudflare Workers](https://mabbs.github.io/2024/07/03/ai-summary.html) | Einführung der Blog-AI-Zusammenfassung mithilfe der Cloudflare Workers+Workers AI+D1-Datenbank.| | Aktiv |
| [RSS-Abonnement-Push-System mit Cloudflare Worker, Hono und Telegram Bot API bauen](https://calpa.me/blog/build-rss-subscription-push-system-with-cloudflare-worker-hono-telegram-bot-api/) | Ausführliche Anleitung zum Einsatz von Cloudflare Worker, Hono Framework und Telegram Bot API, um ein serverloses System zu bauen, das RSS-Feeds überwacht und Updates an Telegram-Kanäle pusht. Vollständig serverlos, geeignet für Einzelentwickler und kleine Teams, unterstützt geplante Aufgaben und Duplikatvermeidung. | |Aktiv|

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
| [Siri Ultra](https://github.com/fatwang2/siri-ultra) |Der Assistent läuft auf Cloudflare Workers und kann mit jedem LLM-Modell arbeiten.|  | In Wartung|
| [GitPush](https://github.com/fatwang2/gitpush) |Ein auf Cloudflare Workflow, Workers AI und Email Routing basierendes GitHub-Projekt-Update-Abonnement-Tool. Sie können GitHub-Projekte abonnieren und Benachrichtigungen per E-Mail mit KI-generierten Zusammenfassungen der Updates erhalten.| | In Wartung|
| [CloudFlare Radar](https://radar.cloudflare.com/scan) | Überprüfen Sie die Technologie-Stack einer Webseite. | | Wird gewartet |
| [wr.do](https://github.com/oiov/wr.do) | Ein auf Cloudflare basierendes Multi-Tenant-DNS-Verteilungssystem. Open-Source und bietet kostenlose DNS-Auflösung und Kurzlink-Generierung an. |  https://wr.do |Aktiv |
| [cloudflare-proxy-sites](https://github.com/seadfeng/cloudflare-proxy-sites) | Ein Cloudflare Workers-Web-Proxy mit Subdomain-Zugriffsmethode. | [Demo](https://www.proxysites.ai.serp.ing/) | Aktiv |
| [web-archive](https://github.com/Ray-D-Song/web-archive) | Basierend auf Cloudflare ist ein kostenloses Tool zum Archivieren und Teilen von Webseiten. Es enthält ein Browser-Plugin und einen Dienst, der auf Cloudflare-Seiten läuft. | https://github.com/Ray-D-Song/web-archive | Aktiv |
| [melody-auth](https://github.com/ValueMelody/melody-auth) | Ein OAuth- und Authentifizierungssystem basierend auf Cloudflare Workers, D1 und KV. | <https://auth.valuemelody.com/> | Aktiv |
| [Cloudflare-KV-Manager](https://github.com/som3canadian/Cloudflare-KV-Manager) | Das fehlende Tool für Ihre Cloudflare KV. Eine vollständigere und einfachere Lösung zum Verwalten von Cloudflare KV-Speicher. Enthält eine Weboberfläche und eine kleine Python-Bibliothek. | <https://kv-demo.somecanadian.com> | Aktiv |
| [CF-TOOLS](https://github.com/MainPoser/cf-tools) | Integrieren Sie gängige Entwicklungstools, KI-Assistenten usw. | <https://cf-tools.tianyao.qzz.io/> | Wird aktualisiert |
| [subpool-worker](https://github.com/illusionlie/subpool-worker) | Leichtgewichtiger Abonnement-Pool-Dienst zum Verwalten und Verteilen von Proxy-Abonnement-Links. |  | Aktiv gepflegt |
| [AWS-AccessBridge](https://github.com/Rexezuge-CloudflareWorkers/AWS-AccessBridge) | AWS Multi-Accounts-Verwaltung und Anmeldung |  | Aktiv gepflegt |
| [Cloudflare-Clist](https://github.com/ooyyh/Cloudflare-Clist) | Ein alist-ähnlicher aggregierter Speicherverwaltungsdienst auf Basis von Cloudflare Workers | <https://down.ohyraw.qzz.io> | Aktiv gepflegt |
| [sync-your-cookie](https://github.com/jackluson/sync-your-cookie) | Browser-Erweiterung zum Synchronisieren von Cookies mit Cloudflare KV oder GitHub Gist. Unterstützt LocalStorage, Auto Merge und Auto Push Regeln für verschiedene Websites, protobuf-verschlüsselte Übertragung und Verwaltungspanel. | | Wird gewartet |
| [myip](https://github.com/hoa-js/examples/tree/master/myip) | IP-Informationserkennungs-Website basierend auf Cloudflare Workers. Unterstützt One-Click-Bereitstellung, erstellt mit hoajs. | <https://myip.hoa-js.com/> | Wird gewartet |
| [2fa](https://github.com/hoa-js/examples/blob/master/2fa/index.js) | 2FA-Generierungs-Website basierend auf Cloudflare Workers. Unterstützt One-Click-Bereitstellung, erstellt mit hoajs. | <https://2fa.hoa-js.com/> | Wird gewartet |
| [tempnote](https://github.com/hoa-js/examples/blob/master/tempnote/tempnote.js) | Temporäre Notiz-Website basierend auf Cloudflare Workers & KV. Generiert zufällige Notizadressen, responsives Design, unterstützt benutzerdefinierte Notizadressen, One-Click-Bereitstellung, erstellt mit hoajs. | <https://tempnote.hoa-js.com/> | Wird gewartet |
| [CloudNav-](https://github.com/sese972010/CloudNav-) | Navigation, die auf Cloudflare gehostet werden kann, mit Chrome-Plugin für One-Click-Bookmarking. Leichtgewichtige Navigation, fokussiert auf Praktikabilität. | | Wird gewartet |
| [memos-worker](https://github.com/souvenp/memos-worker) | Notizen- und Wissensbasis powered by Cloudflare. Vollständige Markdown-Unterstützung, Dateianhänge, öffentliche Freigabe, Telegram-Integration, leistungsstarke Organisation, Wissensbasis, hochgradig anpassbar, extreme Leistung und niedrige Kosten, Datensouveränität. | | Wird gewartet |
| [whisper_cloudflare](https://github.com/thun888/whisper_cloudflare) | Online-Audio-Transkriptionstool basierend auf Whisper-Modell, auf Cloudflare bereitgestellt. Konvertiert Audiodateien in Text und unterstützt SRT-Untertitelgenerierung. | | Wird gewartet |
| [micro-notepad](https://github.com/thun888/micro-notepad/) | Mini-Notizblock, Cloudflare-Worker-Implementierung von [pereorga/minimalist-web-notepad](https://github.com/pereorga/minimalist-web-notepad). | | Wird gewartet |
| [cf-page-publish-mcp](https://github.com/Actrue/cf-page-publish-mcp) | Cloudflare-Seitenveröffentlichungs-MCP-Tool, das HTML-Seiten auf Cloudflare Workers veröffentlichen kann. Kann über MCP mit KI verbinden. | | Wird gewartet |


## Tutorials

| Name | Merkmale | Online-Adresse | Status |
| --- | --- | --- | --- |
| [cloudflare-quickstart](https://github.com/zgimszhd61/cloudflare-quickstart) | Ein Schnelleinstiegsführer, der Ihnen hilft, mit Cloudflare Workers zu beginnen. | | Wird aktualisiert |
| [cloudflare-tunnel](https://dmesg.app/cloudflare) | Eine Reihe von technischen Blogs darüber, wie man Cloudflare Zero Trust verwendet, um ein großes internes Netzwerk zu erstellen und Probleme mit blockierten Servern zu lösen. | | Wird aktualisiert |
| [cloudflare-worker-gmail-resend-enterprise-email](https://cleanclip.cc/zh/developer/cloudflare-worker-gmail-resend-enterprise-email) | Cloudflare + Gmail + Resend: Holen Sie sich in zehn Minuten ganz einfach eine kostenlose Firmen-E-Mail. |  | Wird aktualisiert |

## Gruppe

[Eine Gruppe](https://t.me/indiehackertools)

## Mitwirkende

<a href="https://github.com/zhuima/awesome-cloudflare/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=zhuima/awesome-cloudflare" />
</a>

## Sternenhistorie

[![Sternverlauf Diagramm](https://api.star-history.com/svg?repos=zhuima/awesome-cloudflare&type=Timeline)](https://star-history.com/#zhuima/awesome-cloudflare&Timeline)
