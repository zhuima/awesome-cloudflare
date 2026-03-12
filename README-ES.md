<div align="center">

<h1 align="center">Awesome Cloudflare <img src="https://img.shields.io/github/stars/zhuima/awesome-cloudflare?label=Estrellas" alt="estrellas"></h1>

Este repositorio solo incluye herramientas de código abierto basadas en Cloudflare, proporcionando un conjunto de herramientas que ahorran tiempo y esfuerzo para desarrolladores independientes en sus primeras etapas de exploración, en continua actualización...

[Chino](./README.md) / [Inglés](./README-EN.md) / [Español](./README-ES.md) / [Alemán](./README-DE.md)

![awesome-cloudflare](./docs/awesome-cloudflare-en.svg)

</div>

# [<img src="https://img.techrk1688.eu.org/file/e44951f61086ae4dc9591.png" width="250" align="right" alt="Cloudflare">](https://www.cloudflare.com)

> [![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&vCenter=true&multiline=true&random=false&height=80&lines=Proyectos+seleccionados+de;+Cloudflare+para+Internet+guías,;+blogs+y+otros+recursos+listados.)](https://git.io/typing-svg)

Cloudflare, conocido como el Bodhisattva cibernético, ofrece servicios de red de entrega de contenido (CDN), mitigación de DDoS, seguridad en Internet y servicios de servidor de nombres de dominio distribuido (DNS), ubicado entre el visitante y el proveedor de hosting de los usuarios de Cloudflare, actuando como un proxy inverso para los sitios web.

**Criterios de inclusión:**

- Ayudar, pero no limitado a, desarrolladores independientes para mejorar la eficiencia del desarrollo
- Ayudar, pero no limitado a, desarrolladores independientes para reducir costos
- Suficientemente simple y conveniente

Se invita a contribuir con PR y issues para actualizaciones. Si tienes algún problema durante el despliegue o la operación, puedes crear un issue o contactar en privado para consultas.

## Versión en línea

[Navegación en línea increíble de Cloudflare](https://cloudflare.chuhai.tools)

## Contenidos

- [](#)
  - [Versión en línea](#versión-en-línea)
  - [Contenidos](#contenidos)
  - [Hosting de imágenes](#hosting-de-imágenes)
  - [Correo electrónico](#correo-electrónico)
  - [Blog](#blog)
- [Andamiaje](#andamiaje)
  - [Enlaces cortos](#enlaces-cortos)
  - [Análisis de sitios web](#análisis-de-sitios-web)
  - [Túneles](#túneles)
  - [Aceleración](#aceleración)
  - [Compartir archivos](#compartir-archivos)
  - [Pruebas de velocidad](#pruebas-de-velocidad)
  - [Monitoreo](#monitoreo)
  - [Artículos](#artículos)
  - [Otros](#otros)
  - [Tutoriales](#tutoriales)
  - [Grupo](#grupo)
  - [Colaboradores](#colaboradores)
  - [Historial de Estrellas](#historial-de-estrellas)

## Hosting de imágenes

| Nombre | Características | Dirección en línea | Estado |
| --- | --- | --- | --- |
| [Telegraph-Image-Hosting](https://github.com/missuo/Telegraph-Image-Hosting) | Uso de Telegraph para alojamiento gratuito de imágenes | | No se mantiene |
| [cf-image-hosting](https://github.com/ifyour/cf-image-hosting) | Alojamiento ilimitado y gratuito de imágenes en Telegraph, desplegado en Cloudflare. | <https://images.mingming.dev> | En mantenimiento |
| [img-mom](https://github.com/beilunyang/img-mom) | Basado en Cloudflare Workers runtime, ligero y completamente gratuito, soporta múltiples hostings de imágenes (Telegram/Cloudflare R2/Backblaze B2, más hostings en soporte), despliegue rápido. Uso de Wrangler para despliegue rápido | | En mantenimiento |
| [workers-image-hosting](https://github.com/iiop123/workers-image-hosting) | Hosting de imágenes basado en Cloudflare workers, datos almacenados en KV | | En mantenimiento |
| [Telegraph-Image](https://github.com/cf-pages/Telegraph-Image) | Solución gratuita de hosting de imágenes, alternativa a Flickr/imgur. Usando Cloudflare Pages y Telegraph. | <https://im.gurl.eu.org/> | En mantenimiento |
| [cloudflare-worker-image](https://github.com/ccbikai/cloudflare-worker-image) | Manejo de imágenes con Cloudflare Worker, depende de Photon, soporta escalado, recorte, marca de agua, filtros, etc. |  | En mantenimiento |
| [tgState](https://github.com/csznet/tgState) | Sistema de enlaces de archivos usando Telegram como almacenamiento, sin límites de tamaño o formato de archivo. | <https://tgstate.vercel.app>  | En mantenimiento |
| [roim-picx](https://github.com/roimdev/roim-picx) |Una cama de imágenes gratuita basada en CloudFlare Pages y R2. |  |En mantenimiento|
| [CloudFlare-ImgBed](https://github.com/MarSeventh/CloudFlare-ImgBed)  | Un servicio gratuito de alojamiento de imágenes basado en CloudFlare y Telegraph. Este repositorio se basa en <https://github.com/cf-pages/Telegraph-Image> y es una nueva versión de la página frontal del proyecto original. ¡Código abierto, claro, hermoso, animaciones suaves y versátil! | <https://demo-cloudflare-imgbed.pages.dev/> | En mantenimiento |
| [PixR2](https://github.com/WangQueXL/PixR2) |Plataforma de alojamiento y gestión de imágenes con múltiples puntos de entrada basada en Cloudflare Workers + R2 |   |En mantenimiento|

## Correo electrónico

| Nombre | Características | Dirección en línea | Estado |
| --- | --- | --- | --- |
| [vmail](https://github.com/oiov/vmail) | 📫 Herramienta de correo electrónico temporal de código abierto. Soporta envío y recepción de correos. | <https://vmail.dev/> | En mantenimiento |
| [smail](https://github.com/akazwz/smail) | Servicio de correo electrónico temporal | <https://smail.pw/> | En mantenimiento |
| [Email.ML](https://email.ml/) | Un correo electrónico temporal que funciona en la red de Cloudflare |  | No es de código abierto |
| [cloudflare_temp_email](https://github.com/dreamhunter2333/cloudflare_temp_email) | Uso del servicio gratuito de Cloudflare para establecer un correo electrónico temporal |  <https://temp-email.dreamhunter2333.xyz/> | En mantenimiento |
| [mail2telegram](https://github.com/TBXark/mail2telegram) | Este es un bot de Telegram basado en Cloudflare Email Routing Worker que puede convertir correos electrónicos en mensajes de Telegram. Puedes reenviar correos electrónicos de cualquier prefijo al Bot, que luego creará un bot de correo electrónico temporal con direcciones ilimitadas. |  | En mantenimiento |
| [zmail](https://github.com/zaunist/zmail) | Z-Mail - Un servicio de correo electrónico temporal minimalista construido con pages, worker y D1 SQL de CloudFlare, con soporte para recepción de archivos adjuntos. | <https://mail.mdzz.uk/> | En mantenimiento |
| [Alle](https://github.com/bestruirui/Alle) | Cliente de agregación de correo electrónico con IA que incluye extracción de códigos de verificación y clasificación de enlaces. Ofrece servicio de correo temporal. Construido sobre Cloudflare Workers + Next.js, despliegue sin servidor con solo un dominio. | | En mantenimiento |
| [FreeTempMail](https://github.com/PennyJoly/FreeTempMail) | Un servicio de correo temporal gratuito permanente de estilo limpio y minimalista. Protege la privacidad del usuario, soporta internacionalización i18n, listo para usar. Desarrollado con plantilla NuxtPro y Cloudflare. | <https://mail.aitre.cc> | En mantenimiento |

## Blog

| Nombre | Características | Dirección en línea | Estado |
| --- | --- | --- | --- |
| [cloudflare-workers-blog](https://github.com/gdtool/cloudflare-workers-blog) | Este es un programa de blog que funciona en cloudflare workers, usando cloudflare KV como base de datos, sin otras dependencias. Compatible con la velocidad de los blogs estáticos y la flexibilidad de los blogs dinámicos, fácil de configurar sin complicaciones. |   <https://blog.gezhong.vip/> | En mantenimiento |
| [cloudflare-workers-blog](https://github.com/kasuganosoras/cloudflare-worker-blog) | Sistema de blog dinámico implementado con Cloudflare workers + Github, utilizando computación en el borde, sin necesidad de servidores | | Parece que no se mantiene |
| [microfeed](https://github.com/microfeed/microfeed) | Un sistema de gestión de contenidos (CMS) autoalojado y ligero en Cloudflare. Con microfeed, puedes publicar fácilmente varios contenidos (como audio, video, fotos, documentos, posts de blog y URLs externas) en formato web, RSS y JSON. Es la solución perfecta para individuos técnicamente competentes que desean autoalojar su propio CMS sin tener que operar sus propios servidores. | <https://www.microfeed.org/> | En mantenimiento |
| [emaction.frontend](https://github.com/emaction/emaction.frontend) | Basado en Cloudflare D1, implementa la función de Reactions al estilo GitHub, este proyecto es el frontend. | <https://emaction.cool/>| En mantenimiento |
| [emaction.backend](https://github.com/emaction/emaction.backend) | Basado en Cloudflare D1, implementa la función de Reactions al estilo GitHub, este proyecto es el backend. | <https://emaction.cool/> | En mantenimiento |
| [Gins-Blog](https://github.com/IchimaruGin728/Gins-Blog) | Plataforma de blog de alto rendimiento y Agentic-First. Construida en el ecosistema de Cloudflare. Soporta MCP y despliegue Zero-Touch vía OpenClaw. | <https://blog.ichimarugin728.com> | En mantenimiento |

# Andamiaje

| Nombre | Características | Dirección en línea | Estado |
| --- | --- | --- | --- |
| [nextflare](https://github.com/ccbikai/nextflare) | Aplicación Next.js que se ejecuta con Lemon Squeezy en Cloudflare. | <https://nextflare-template.pages.dev/> | Mantenimiento |

## Enlaces cortos

| Nombre | Características | Dirección en línea | Estado |
| --- | --- | --- | --- |
| [short](https://github.com/igengdu/short/) | Un acortador de URL creado con Cloudflare Pages. | <https://d.igdu.xyz/> | En mantenimiento |
| [short](https://github.com/x-dr/short) | Un acortador de URL creado con Cloudflare Pages. | <https://d.131213.xyz/> | En mantenimiento |
| [linklet](https://github.com/harrisonwang/linklet) | Un acortador de URL creado con Cloudflare Pages. Este está basado en un modelo API, ofreciendo más escenarios de uso. | <https://wss.so/> | En mantenimiento |
| [Url-Shorten-Worker](https://github.com/crazypeace/Url-Shorten-Worker) | Acceso a la página de operaciones mediante una ruta secreta. Soporta enlaces cortos personalizados. Servicio API no público. Caché de página para enlaces cortos establecidos. Caja de texto de enlace largo con pre-búsqueda en localStorage. Añade un botón para eliminar un enlace corto específico. Añade un botón para leer KV. Se transforma en un bloc de notas en línea Pastebin. Se transforma en un host de imágenes Image Hosting. Un acortador de URL creado con Cloudflare worker y KV. | <https://urlsrv.crazypeace.workers.dev/bodongshouqulveweifengci> | En mantenimiento |
| [duanwangzhi](https://github.com/Closty/duanwangzhi) | Acorta tus enlaces sin necesidad de un servicio, ya que se basa en la funcionalidad de los trabajadores de Cloudflare, con un estilo minimalista. |  | Parece que no se mantiene |
| [Url-Shorten-Worker](https://github.com/horsemail/Url-Shorten-Worker) | Este es un fork de Url-Shorten-Worker de crazypeace, utiliza una ruta secreta para acceder a la página de operaciones. Soporta enlaces cortos personalizados. Servicio API no público. Caché de página para enlaces cortos establecidos. Caja de texto de enlace largo con pre-búsqueda en localStorage. Añade un botón para eliminar un enlace corto específico. Añade un botón para leer KV. Se transforma en un bloc de notas en línea Pastebin. Se transforma en un host de imágenes Image Hosting. Un acortador de URL creado con Cloudflare worker y KV. | <https://1way.eu.org/bodongshouqulveweifengci> | En mantenimiento |
| [CloudFlare-Pages-UrlShorten](https://github.com/Jiaocz/CloudFlare-Pages-UrlShorten) | Una herramienta de enlace corto multifuncional. |  | En mantenimiento |
| [Url-Shorten-Worker](https://github.com/Monopink/Url-Shorten-Worker/) | Optimización de la página sobre la base de la funcionalidad original y la rama de crazypeace, añadiendo usuarios administradores, identidades de visitantes, funcionalidad de coincidencia de expresiones regulares, soporte para configuración de variables de entorno, y otras mejoras detalladas. | <https://url-shortener-demo.jhw.li/> | En mantenimiento |
| [CloudflareWorker-KV-UrlShort](https://github.com/Ai-Yolo/CloudflareWorker-KV-UrlShort) | Un acortador de URL creado con Cloudflare Worker, soporta una página de inicio personalizada, Menu Short, y compartir URL de enlaces cortos, texto y páginas web. |  | En mantenimiento |
| [Sink](https://github.com/ccbikai/Sink)  |Un acortador de enlaces simple / rápido / seguro con análisis, 100% operado en Cloudflare.| <https://sink.cool/>| En mantenimiento|
| [short](https://github.com/molikai-work/short) | Un proyecto modificado basado en x-dr/short, que añade funciones como la configuración de contraseñas para enlaces cortos, la gestión de enlaces cortos, el uso de CAPTCHA de Turnstile, la gestión de dominios en lista negra, la configuración de páginas de redirección y el uso de múltiples dominios. | [Demo](https://c1n.top/) | Mantenido |



## Análisis de sitios web

| Nombre | Características | Dirección en línea | Estado |
| --- | --- | --- | --- |
| [analytics_with_cloudflare](https://github.com/yestool/analytics_with_cloudflare) | Contador de visitantes de páginas web gratuito y de código abierto, Webviso es un servicio de estadísticas de visitantes web completamente gratuito implementado con el servicio worker de Cloudflare y la base de datos Cloudflare D1. Ofrece funcionalidades similares al contador minimalista de páginas web "No Garlic". Webviso es completamente de código abierto, permitiendo personalizaciones según tus necesidades. Desplegable rápidamente gracias a la arquitectura de microservicios de Cloudflare. | <https://webviso.yestool.org/> | En mantenimiento |
| [counterscale](https://github.com/benvinegar/counterscale) | Counterscale es un rastreador y panel de análisis web simple, similar en efecto a umami, que puedes alojar tú mismo en Cloudflare. Está diseñado para ser fácil de desplegar y mantener, y tus costos operativos deberían ser casi nulos incluso bajo tráfico alto (asumiendo que el plan gratuito de Cloudflare puede manejar hasta 100,000 clics por día). | <https://counterscale.dev/> | En mantenimiento |

## Túneles

| Nombre | Características | Dirección en línea | Estado |
| --- | --- | --- | --- |
| [Cloudflared-web](https://github.com/WisdomSky/Cloudflared-web) | Cloudflared-web es una imagen de docker que empaqueta el CLI de cloudflared y una interfaz web simple para facilitar el inicio/detención de túneles de cloudflare. |  | En mantenimiento |

## Aceleración

| Nombre | Características | Dirección en línea | Estado |
| --- | --- | --- | --- |
| [gh-proxy](https://github.com/hunshcn/gh-proxy) | Proyecto de aceleración para github release, archivos de proyecto y archivos de archivo, soporta clonación. Tiene versiones sin servidor en Cloudflare Workers y una versión en Python. | <https://gh.api.99988866.xyz/> | En mantenimiento |
| [githubbox](https://github.com/dferber90/githubbox) | Abre rápidamente cualquier repositorio de GitHub en CodeSandbox. |  | Parece que no se mantiene |
| [gh-proxy](https://github.com/crazypeace/gh-proxy) |Un proyecto para acelerar las versiones, archivos de archivo y archivos de proyecto de GitHub. Soporta api.github.com y git.io. | <https://ghproxy.lvedong.eu.org/> |Mantenido|
| [cf-proxy-ex](<https://github.com/1234567Yang/cf-proxy-ex>)  |Proxy super de Cloudflare, configurando un proxy gratuito usando el trabajador de Cloudflare. | <https://y.demo.wvusd.homes/> |Mantenido|
| [cloudflare-docker-proxy](https://github.com/ciiiii/cloudflare-docker-proxy) | Un proyecto llamado cloudflare-docker-proxy, que es un proxy de registro de Docker Hub que se ejecuta en Cloudflare Worker. |  | En mantenimiento |
| [CF-Workers-docker.io](https://github.com/cmliu/CF-Workers-docker.io) | Este proyecto es una herramienta de proxy de imagen de Docker basada en Cloudflare Workers. Puede retransmitir solicitudes al repositorio oficial de imágenes de Docker, resolviendo restricciones de acceso y acelerando el acceso. | <https://docker.fxxk.dedyn.io/> | En mantenimiento |
| [cf-workers-proxy](https://github.com/jonssonyan/cf-workers-proxy) | En teoría, el proxy inverso HTTP de Cloudflare Workers admite la transferencia de cualquier nombre de dominio bloqueado. Solo necesita configurar la variable de entorno PROXY_HOSTNAME en el nombre de dominio bloqueado. |  | En mantenimiento |
| [gemini-balance-do](https://github.com/zaunist/gemini-balance-do) | Basado en Cloudflare Worker y Durable Objects, este proyecto implementa un relé de API de Gemini (equilibrio de carga de múltiples claves) para un acceso estable con IP de EE. UU. a Gemini. | https://github.com/zaunist/gemini-balance-do | Mantenido |

## Compartir archivos

| Nombre | Características | Dirección en línea | Estado |
| --- | --- | --- | --- |
| [pastebin-worker](https://github.com/SharzyL/pastebin-worker) | Presentando un Pastebin de código abierto desplegado en Cloudflare Workers, que permite compartir "texto" o "archivos" a través de URL. Como el plan gratuito de CF: permite 100,000 lecturas diarias, 1,000 escrituras y operaciones de eliminación, con un límite de tamaño de 25 MB, suficiente para uso ligero. Despliégalo tú mismo o úsalo directamente. También tiene funciones de "tiempo de eliminación" y "contraseña", permitiendo establecer un tiempo después del cual tu paste será eliminado. Excelente para compartir archivos y texto en Twitter. | <https://shz.al/> | En mantenimiento |
| [FileWorker](https://github.com/yllhwa/FileWorker) | Un portapapeles en línea/archivo compartido que funciona en Cloudflare Worker. |  | En mantenimiento |
| [dingding](https://github.com/iiop123/dingding) | Una herramienta de transferencia de archivos basada en Cloudflare Workers, con archivos almacenados en Cloudflare KV. |  | Parece que no se mantiene |

## Pruebas de velocidad

| Nombre | Características | Dirección en línea | Estado |
| --- | --- | --- | --- |
| [CloudflareSpeedTest](https://github.com/XIU2/CloudflareSpeedTest) | Muchos sitios web internacionales utilizan Cloudflare CDN, pero las IP asignadas a los visitantes del interior de China no son amigables (alta latencia, muchas pérdidas de paquetes, velocidad lenta). Aunque Cloudflare ha publicado todos los rangos de IP, encontrar uno que se adapte a ti entre tantos puede ser agotador, por lo que se creó este software. |  | En mantenimiento |
| [SpeedTest](https://speed.cloudflare.com/) | Herramienta oficial de SpeedTest. |  | En funcionamiento |
| [ip-check](https://github.com/lovegitgit/ip-check) | Una herramienta de prueba de velocidad de CDN de Cloudflare basada en Python que admite múltiples formas de ingresar IPs (archivos de texto, IPv4/IPv6, puertos, dominios preferidos, etc.), puertos personalizables, filtrado por ubicación geográfica de IP y filtrado por nombre de organización de IP. | | En mantenimiento |

## Monitoreo

| Nombre | Características | Dirección en línea | Estado |
| --- | --- | --- | --- |
| [UptimeFlare](https://github.com/lyc8503/UptimeFlare) | Una herramienta de monitoreo de sitios web sin servidor basada en Cloudflare Worker. Admite monitoreo de puertos para múltiples protocolos, incluidos HTTP/HTTPS/TCP. Puede iniciar comprobaciones geográficamente específicas desde cientos de ciudades en todo el mundo, con parámetros de solicitud personalizables y reglas de validación de respuesta, adaptable para diversos escenarios de monitoreo. | <https://uptimeflare.pages.dev/> | En mantenimiento |
| [cf-workers-status-page](https://github.com/eidam/cf-workers-status-page) | Monitorea tu sitio web, muestra el estado (incluido el historial diario) y recibe notificaciones de Slack cuando cambia el estado del sitio web. Utiliza Cloudflare Workers, disparadores CRON y almacenamiento KV. | <https://status-page.eidam.dev/> | En mantenimiento |
| [xugou](https://github.com/zaunist/xugou)| Una herramienta de monitoreo de sitios web y servidores basada en CloudFlare. | https://xugou.mdzz.uk/ |  En mantenimiento |
| [deploy-mcp](https://github.com/alexpota/deploy-mcp) | Rastreador universal de despliegues para asistentes de IA con insignias de estado en vivo y monitoreo de despliegues, incluyendo soporte para Cloudflare Pages. | https://deploy-mcp.io | Activo |

## Artículos

| Nombre | Características | Dirección en línea | Estado |
| --- | --- | --- | --- |
| [workers](https://igdux.com/workers) | Colección de proyectos destacados de Cloudflare Workers. |  | Activo |
| [accelerate-and-secure-with-cloudflared](https://nova.moe/accelerate-and-secure-with-cloudflared/) | Este es un blog que te enseña a usar Cloudflare Argo Tunnel (cloudflared) para acelerar y proteger tu sitio web. |  | Activo |
| [jsonbin](https://www.owenyoung.com/blog/jsonbin/) | Despliega un servicio de almacenamiento JSON en Cloudflare Workers. |  | Activo |
| [cronbin](https://www.owenyoung.com/blog/cronbin/) | Despliega un servicio Cron con Dashboard en Cloudflare Workers. |  | Activo |
| [using-cloudflare-worker-proxy-google](https://xiaowangye.org/posts/using-cloudflare-worker-proxy-google/) | Usa un Cloudflare Worker para proxy de sitios de Google. |  | Activo |
| [Use-Cloudflare-Zero-Trust-protect-your-web-applications](https://jiapan.me/2023/Use-Cloudflare-Zero-Trust-protect-your-web-applications/) | Usa Cloudflare Zero Trust para proteger tus aplicaciones web. |  | Activo |
| [Nextjs-app-router-with-cloudflare-r2](https://juejin.cn/post/7306723921717166131) | Cómo usar Cloudflare R2 storage en el directorio app/ de Next.js 13. |  | Activo |
| [cloudflare-webssh-zerotrust](https://josephcz.xyz/technology/network/cloudflare-webssh-zerotrust/) | Configura WebSSH con Cloudflare ZeroTrust. |  | Activo |
| [Alternativa gratuita a CAPTCHA](https://www.cloudflare.com/zh-cn/products/turnstile/) | Producto oficial, una alternativa gratuita a CAPTCHA. |  | Activo |
| [Enviando mensajes a Telegram a través de las funciones de página de Cloudflare](https://liujiacai.net/blog/2024/05/07/telegram-bot-functions/) | Este artículo presenta cómo utilizar funciones de página como direcciones de webhook de GitHub para reenviar eventos específicos a canales de Telegram. | | Activo |
| [Hacer un resumen de la IA del blog con cloudflare Workers](https://mabbs.github.io/2024/07/03/ai-summary.html) | Introduce el uso de la base de datos cloudflare Workers + Workers Ai + D1 para implementar el resumen de Ia del blog.| | Activo |
| [Construir un sistema de suscripción y push RSS con Cloudflare Worker, Hono y Telegram Bot API](https://calpa.me/blog/build-rss-subscription-push-system-with-cloudflare-worker-hono-telegram-bot-api/) | Guía detallada sobre cómo usar Cloudflare Worker, el framework Hono y la API de Telegram Bot para crear un sistema serverless que monitorea fuentes RSS y envía actualizaciones a canales de Telegram. Totalmente sin servidor, ideal para desarrolladores individuales y pequeños equipos, soporta tareas programadas y evita mensajes duplicados. | |Activo|

## Otros

| Nombre | Características | Dirección en línea | Estado |
| --- | --- | --- | --- |
| [silk-privacy-pass-client](https://chromewebstore.google.com/detail/silk-privacy-pass-client/ajhmfdgkijocedmfjonnpjfojldioehi) | Si frecuentemente enfrentas verificaciones CAPTCHA de Cloudflare, puedes usar este plugin oficial de Cloudflare para resolverlo. Una vez instalado, no tendrás que enfrentarte a CAPTCHAs constantemente. | | En mantenimiento |
| [WARP-Clash-API](https://github.com/vvbbnn00/WARP-Clash-API) | Este proyecto te permite usar WARP+ a través de una suscripción, soportando clientes como Clash y Shadowrocket. Incluye una función para acumular tráfico de WARP+ sin límites (obteniendo 1GB cada 18 segundos) y también ofrece una función de selección óptima de IP. Soporta despliegue automático con Docker compose, permitiéndote disfrutar de tu propio nodo privado de alta velocidad de WARP+ sin necesidad de configuraciones adicionales. | | En mantenimiento |
| [ip-api](https://github.com/ccbikai/ip-api) | Rápidamente monta una API para obtener direcciones IP y información geográfica usando Cloudflare Workers, Vercel Edge o Netlify Edge. | <https://html.zone/ip> | En mantenimiento |
| [ChatGPT-Telegram-Workers](https://github.com/TBXark/ChatGPT-Telegram-Workers) | Despliega fácilmente tu propio bot de Telegram ChatGPT en Cloudflare Workers, con tutoriales detallados en video y texto, simple incluso para principiantes. | | En mantenimiento |
| [RSSWorker](https://github.com/yllhwa/RSSWorker) | RSSWorker es una herramienta de suscripción RSS ligera que puede ser desplegada en Cloudflare Worker. | | En mantenimiento |
| [deeplx-for-cloudflare](https://github.com/ifyour/deeplx-for-cloudflare) | Despliega DeepLX en Cloudflare. | <https://deeplx.mingming.dev/> | En mantenimiento |
| [sub_converter_convert](https://github.com/zzNeutrino/sub_converter_convert) | Herramienta para convertir enlaces de suscripción de ssr/v2ray. | | Parece que no se mantiene |
| [telegram-counter](https://github.com/iamshaynez/telegram-counter) | Un backend para Telegram escrito puramente en Cloudflare Worker y usando la base de datos D1, útil para llevar registros de asistencia en cualquier momento y lugar. | | Parece que no se mantiene |
| [Cloudflare-No-Tracked](https://github.com/fwqaaq/Cloudflare-No-Tracked) | Elimina los enlaces de seguimiento de sitios como Bilibili y Xiaohongshu, también disponible en versión bot de Telegram. | <https://notracked.fwqaq.us/> | En mantenimiento |
| [dnschecker](https://dnschecker.org/) | Herramienta recomendada oficialmente por Cloudflare para verificar la resolución de dominios. | | Activo |
| [blockedinchina](https://www.comparitech.com/privacy-security-tools/blockedinchina/) | Herramienta recomendada oficialmente por Cloudflare para verificar si un dominio está bloqueado en China. | | Activo |
| [Serverless Cloud Notepad](https://github.com/s0urcelab/serverless-cloud-notepad) | Un bloc de notas en la nube que funciona en Cloudflare, fácil de configurar, útil para transferencias de texto temporales y soporta sintaxis Markdown y cifrado. | | Parece que no se mantiene |
| [prisma-with-cloudflare-d1](https://www.prisma.io/docs/orm/overview/databases/cloudflare-d1) | Este documento explica cómo interactuar con la base de datos Cloudflare D1 usando Prisma, comenzando con los conceptos básicos y la arquitectura de Prisma, seguido de detalles sobre cómo conectar y consultar la base de datos Cloudflare D1, y terminando con algunos consejos prácticos y mejores prácticas para usar Prisma con Cloudflare D1. | | Activo |
| [cohere2openai-cf-worker](https://github.com/ckt1031/cohere2openai-cf-worker) | Un simple Cloudflare Worker que convierte la API de Cohere en la API de OpenAI, fácil de desplegar en Cloudflare Workers. | | En mantenimiento |
| [cohere2openai](https://github.com/beanqi/cohere2openai) | Cloudflare Worker que convierte la API de Cohere en la API de OpenAI. | | En mantenimiento |
| [locnode](https://github.com/minlearn/locnode) | Aplicación comunitaria federada ligera y autoalojada que funciona en Cloudflare, la primera de su tipo que puede operar en CF. | <https://locnode.com/> | En mantenimiento |
| [Siri Ultra](https://github.com/fatwang2/siri-ultra) |El asistente se ejecuta en Cloudflare Workers y puede trabajar con cualquier modelo LLM.|  | En mantenimiento|
| [GitPush](https://github.com/fatwang2/gitpush) |Una herramienta de suscripción a actualizaciones de proyectos de GitHub construida sobre Cloudflare Workflow, Workers AI y Email Routing. Puedes suscribirte a los proyectos de GitHub que sigues y recibir notificaciones por correo electrónico con resúmenes de actualizaciones generados por IA.| | En mantenimiento|
| [CloudFlare Radar](https://radar.cloudflare.com/scan) | Verifique el stack tecnológico de un sitio web. | | En mantenimiento |
| [wr.do](https://github.com/oiov/wr.do) | Un sistema de distribución de DNS multiinquilino basado en Cloudflare. Código abierto y proporciona resolución de DNS y generación de enlaces cortos de forma gratuita. | https://wr.do |  En mantenimiento |
| [cloudflare-proxy-sites](https://github.com/seadfeng/cloudflare-proxy-sites) | Un proxy web de Cloudflare Workers con método de acceso mediante subdominios. | [Demo](https://www.proxysites.ai.serp.ing/) | En mantenimiento |
| [web-archive](https://github.com/Ray-D-Song/web-archive) | Herramienta gratuita de archivo y compartición de páginas web basada en Cloudflare. Incluye un complemento de navegador y un servicio que se ejecuta en la página de Cloudflare. | https://github.com/Ray-D-Song/web-archive | Aktiv |
| [melody-auth](https://github.com/ValueMelody/melody-auth) | Un sistema de autenticación y oauth basado en Cloudflare workers, D1 y KV. | <https://auth.valuemelody.com/> | Activo |
| [Cloudflare-KV-Manager](https://github.com/som3canadian/Cloudflare-KV-Manager) | La herramienta que falta para tu Cloudflare KV. Una solución más completa y sencilla para gestionar el almacenamiento de Cloudflare KV. Incluye una interfaz web y una pequeña biblioteca de Python. | <https://kv-demo.somecanadian.com> | Activo |
| [CF-TOOLS](https://github.com/MainPoser/cf-tools) | Integrigi oftajn programadilon kaj AI-asistantojn. | <https://cf-tools.tianyao.qzz.io/> | Actualizando |
| [subpool-worker](https://github.com/illusionlie/subpool-worker) | Servicio ligero para la gestión y distribución de suscripciones proxy. |  | Mantenido activamente |
| [AWS-AccessBridge](https://github.com/Rexezuge-CloudflareWorkers/AWS-AccessBridge) | Gestión y acceso de múltiples cuentas de AWS |  | Mantenido activamente |
| [Cloudflare-Clist](https://github.com/ooyyh/Cloudflare-Clist) | Un servicio de gestión de almacenamiento agregado similar a alist basado en Cloudflare Workers | <https://down.ohyraw.qzz.io> | Mantenido activamente |
| [sync-your-cookie](https://github.com/jackluson/sync-your-cookie) | Extensión de navegador para sincronizar cookies con Cloudflare KV o GitHub Gist. Soporta LocalStorage, reglas Auto Merge y Auto Push para diferentes sitios, transmisión codificada en protobuf y panel de gestión. | | En mantenimiento |
| [myip](https://github.com/hoa-js/examples/tree/master/myip) | Sitio web de detección de información IP basado en Cloudflare Workers. Soporta despliegue con un clic, construido con hoajs. | <https://myip.hoa-js.com/> | En mantenimiento |
| [2fa](https://github.com/hoa-js/examples/blob/master/2fa/index.js) | Sitio web de generación 2FA basado en Cloudflare Workers. Soporta despliegue con un clic, construido con hoajs. | <https://2fa.hoa-js.com/> | En mantenimiento |
| [tempnote](https://github.com/hoa-js/examples/blob/master/tempnote/tempnote.js) | Sitio web de notas temporales basado en Cloudflare Workers & KV. Genera direcciones de notas aleatorias, diseño responsivo, soporta direcciones de notas personalizadas, despliegue con un clic, construido con hoajs. | <https://tempnote.hoa-js.com/> | En mantenimiento |
| [CloudNav-](https://github.com/sese972010/CloudNav-) | Navegación que puede ser alojada en Cloudflare, con complemento de Chrome para guardar favoritos en la navegación con un clic. Navegación ligera enfocada en practicidad. | | En mantenimiento |
| [memos-worker](https://github.com/souvenp/memos-worker) | Notas y base de conocimientos impulsada por Cloudflare. Soporte completo de Markdown, archivos y adjuntos, intercambio público, integración con Telegram, poderosa organización, base de conocimientos, altamente personalizable, rendimiento extremo y bajo costo, soberanía de datos. | | En mantenimiento |
| [whisper_cloudflare](https://github.com/thun888/whisper_cloudflare) | Herramienta de transcripción de audio en línea basada en el modelo Whisper, desplegada en Cloudflare. Convierte archivos de audio a texto y soporta generación de subtítulos SRT. | | En mantenimiento |
| [micro-notepad](https://github.com/thun888/micro-notepad/) | Mini bloc de notas, implementación de Cloudflare Worker de [pereorga/minimalist-web-notepad](https://github.com/pereorga/minimalist-web-notepad). | | En mantenimiento |
| [cf-page-publish-mcp](https://github.com/Actrue/cf-page-publish-mcp) | Herramienta MCP de publicación de páginas Cloudflare que puede publicar páginas HTML en Cloudflare Workers. Puede conectarse a IA a través de MCP. | | En mantenimiento |
| [ShotOG](https://github.com/nicepkg/shotog) | API de generación de imágenes OG de código abierto que se ejecuta en Cloudflare Workers. 8 plantillas, generación por lotes, fuentes personalizadas, renderizado en el borde ~50ms. | <https://shotog.2214962083.workers.dev> | En mantenimiento |
| [Keep My Claw](https://github.com/Ryce/keepmyclaw) | Herramienta de respaldo en la nube cifrado para agentes de IA construida sobre Cloudflare Workers + D1 + R2. Soporta copias de seguridad automáticas programadas, cifrado AES-256 del lado del cliente y restauración con un solo comando en cualquier dispositivo. Diseñada para espacios de trabajo OpenClaw. | <https://keepmyclaw.com> | En mantenimiento |


## Tutoriales

| Nombre | Características | Dirección en línea | Estado |
| --- | --- | --- | --- |
| [cloudflare-quickstart](https://github.com/zgimszhd61/cloudflare-quickstart) | Una guía rápida para ayudarte a comenzar con Cloudflare Workers. | | Actualizando |
| [cloudflare-tunnel](https://dmesg.app/cloudflare) | Una serie de blogs técnicos sobre cómo usar Cloudflare Zero Trust para crear una gran red interna y resolver problemas de servidores bloqueados. | | Actualizando |
| [cloudflare-worker-gmail-resend-enterprise-email](https://cleanclip.cc/zh/developer/cloudflare-worker-gmail-resend-enterprise-email) | Cloudflare + Gmail + Resend: Obtén un correo electrónico empresarial gratuito en diez minutos fácilmente.|  | Actualizando |

## Grupo

[Un Grupo](https://t.me/indiehackertools)

## Colaboradores

<a href="https://github.com/zhuima/awesome-cloudflare/graphs/contributors">
   <img src="https://contrib.rocks/image?repo=zhuima/awesome-cloudflare" />
</a>

## Historial de Estrellas

[![Gráfico del Historial de Estrellas](https://api.star-history.com/svg?repos=zhuima/awesome-cloudflare&type=Timeline)](https://star-history.com/#zhuima/awesome-cloudflare&Timeline)
