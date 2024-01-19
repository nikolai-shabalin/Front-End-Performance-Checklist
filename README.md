<h1 align="center">
<br>
  <a href="https://github.com/thedaviddias/Front-End-Performance-Checklist"><img src="https://raw.githubusercontent.com/thedaviddias/Front-End-Performance-Checklist/master/images/logo-front-end-performance-checklist.jpg" alt="Front-End Performance Checklist" width="170"></a>
  <br>
    <br>
  Front-End Performance Checklist
  <br>
</h1>

---

<h3 align="center">🚨 В настоящее время мы работаем над новой версией frontendchecklist.io <br>(которая будет включать в себя текущую производительность).<br>Не стесняйтесь <a href="https://github.com/thedaviddias/Front-End-Checklist/discussions/513">обсуждать</a> любые функции, которые вы хотели бы видеть. Спасибо за поддержку! </h3>

---

<h4 align="center">🎮 Единственный контрольный список производительности фронтальной части, который работает быстрее остальных.</h4>
<p align="center">Одно простое правило: "Проектируйте и кодируйте с учетом производительности".</p>

<p align="center">
  <a href="#как-использовать">Как использовать</a> • <a href="#contributing">Вклад</a> • <a href="https://www.producthunt.com/posts/front-end-performance-checklist">Охота за продуктами</a>
</p>

<p align="center">
  <a href="https://github.com/JohnsenZhou/Front-End-Performance-Checklist">🇨🇳</a>
  <a href="https://github.com/WilliamDASILVA/Front-End-Performance-Checklist">🇫🇷</a>
  <a href="https://github.com/ParkSB/Front-End-Performance-Checklist">🇰🇷</a>
  <a href="https://github.com/fernandofawkes/Front-End-Performance-Checklist">🇵🇹</a>
  <a href="https://github.com/lex111/Front-End-Performance-Checklist">🇷🇺</a>
  <a href="https://github.com/GameWith/Front-End-Performance-Checklist">🇯🇵</a>
  <a href="https://github.com/ms-fadaei/Front-End-Performance-Checklist">🇮🇷</a>
</p>

## Введение

Производительность - это огромная тема, но она не всегда относится к "бэкенду" или "админке": это также и ответственность Front-End-разработчика. Контрольный список производительности Front-End - это исчерпывающий список элементов, которые вы должны проверить или хотя бы знать о них, как Front-End-разработчик, и применить в своем проекте (личном и профессиональном).

### Как использовать?

Каждое правило будет содержать абзац, объясняющий, почему это правило важно и как его можно исправить. Для более глубокой информации вы должны найти ссылки, которые укажут на 🛠 инструменты, 📖 статьи или 📹 видео, которые могут дополнить контрольный список.

Все пункты **Конечного контрольного списка производительности** важны для достижения наивысшей оценки производительности, но вам нужен индикатор, который поможет вам в конечном итоге определить приоритетность одних правил по отношению к другим. Существует 3 уровня приоритетности:

* ![Низкий][low] означает, что элемент имеет **низкий** приоритет.
* ![Средний][medium] означает, что этот пункт имеет **средний** приоритет. Вам не следует избегать выполнения этого пункта.
* ![Высокий][high] означает, что этот пункт имеет **высокий** приоритет. Вы не можете не следовать этому правилу и не вносить рекомендованные исправления.

### Инструменты производительности

Список инструментов, которые вы можете использовать для тестирования или мониторинга вашего сайта или приложения:

 * 🛠 [WebPagetest - Тест на производительность и оптимизацию сайта](https://www.webpagetest.org/)
 * 🛠 ☆ [Dareboost: Тест скорости сайта и анализ сайта](https://www.dareboost.com/) (use the coupon WPCDD20 for -20%)
 * 🛠 [Treo: Мониторинг скорости страницы](https://treo.sh/?ref=perfchecklist)
 * 🛠 [GTmetrix | Оптимизация скорости и производительности сайтаn](https://gtmetrix.com/)
 * 🛠 [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/)
 * 🛠 [Web.dev](https://web.dev/measure)
 * 🛠 [Pingdom Тест скорости веб-сайта](https://tools.pingdom.com)
 * 📖 [Сделайте веб быстрее | Google Developers](https://developers.google.com/speed/)
 * 🛠 [Sitespeed.io - Добро пожаловать в удивительный мир Web Performance](https://www.sitespeed.io/)
 * 🛠 [Calibre](https://calibreapp.com/)
 * 🛠 [Website Speed Test | Проверка производительности веб-сайта&raquo; Dotcom-Tools](https://www.dotcom-tools.com/website-speed-test.aspx)
 * 🛠 [Мониторинг работоспособности веб-сайтов и серверов - Pingdom](https://www.pingdom.com/product/uptime-monitoring/) ([Free Signup Link](https://www.pingdom.com/free))
 * 🛠 [Робот для проверки работоспособности](https://uptimerobot.com)
 * 🛠 [SpeedCurve: Мониторинг производительности фронтальной части](https://speedcurve.com)
 * 🛠 [PWMetrics - Инструмент CLI и lib для сбора показателей производительности](https://github.com/paulirish/pwmetrics)
 * 🛠 [Varvy - Оптимизация скорости страницы]( https://varvy.com/pagespeed/)
 * 🛠 [Lighthouse - Google]( https://developers.google.com/web/tools/lighthouse/#devtools)
 * 🛠 [Checkbot расширение браузера - Проверяет наилучшие практики производительности веб-сайтов](https://www.checkbot.io/)
 * 🛠 [Yellow Lab Tools | Онлайн-тест для ускорения работы тяжелых веб-страниц](https://yellowlab.tools/)
 * 🛠 [Speedrank - Мониторинг производительности веб-сайтов](https://speedrank.app/)
 * 🛠 [DebugBear - Мониторинг производительности сайта и показателей Lighthouse](https://www.debugbear.com/)
 * 🛠 [packtracker.io - Проверяйте размер пакета webpack при каждом запросе на выгрузку.](https://packtracker.io/)
 * 🛠 [Exthouse - Анализ влияния расширения браузера на производительность веб-сайта](https://github.com/treosh/exthouse)
 * 🛠 [LogRocket - Измерьте производительность фронтэнда в производственных приложениях](https://logrocket.com)

### Ссылки

 * 📹 [Стоимость JavaScript - YouTube](https://www.youtube.com/watch?v=_bzqF05xsC4) ([text version](https://medium.com/@addyosmani/the-cost-of-javascript-in-2018-7d8950fbb5d4))
 * [AddyOsmani.com - Начните составлять бюджет производительности](https://addyosmani.com/blog/performance-budgets/)
 * 📖 [Начните анализировать производительность во время выполнения  |  Google Developers](https://developers.google.com/web/tools/chrome-devtools/evaluate-performance/)
 * 📖 [Состояние интернета | 2018_01_01](https://httparchive.org/reports/state-of-the-web?start=2018_01_01)
 * 📖 [Вес страницы не имеет значения](https://www.speedshop.co/2015/11/05/page-weight-doesnt-matter.html)
 * 📖 [Контрольный список производительности фронтальной части 2021 [PDF, Apple Pages, MS Word]](https://www.smashingmagazine.com/2021/01/front-end-performance-2021-free-pdf-checklist/)
 * 📖 [Проектирование для производительности: эстетика и скорость- By Lara Callender Hogan [eBook, Print]](http://designingforperformance.com/index.html)
 * 📖 [Varvy - Глоссарий по веб-производительности](https://varvy.com/performance/)
 * 📖 [fabkrum/web-performance-resources: Актуальная коллекция ценных ресурсов по веб-производству](https://github.com/fabkrum/web-performance-resources)
 * 📖 [Checkbot - Лучшие методы повышения скорости работы веб-сайтов](https://www.checkbot.io/guide/speed/)
 * 🛠 [Прогрессивный инструментарий - список инструментов сторонних разработчиков, которые можно использовать для повышения производительности страниц.](https://progressivetooling.com/)

---

## HTML

![html]

- [ ] **Минифицированный HTML:** ![medium] HTML-код минифицируется, комментарии, пробелы и новые строки удаляются из рабочих файлов.

    *Почему:*
    > Удаление всех ненужных пробелов, комментариев и атрибутов уменьшит размер HTML, ускорит загрузку страниц сайта и, очевидно, облегчит загрузку для пользователя.

    *Как:*
    > Большинство фреймворков имеют плагины для минификации веб-страниц. Вы можете использовать множество модулей NPM, которые выполнят эту работу за вас автоматически.

    * 🛠 [HTML minifier | Минифицировать код](http://minifycode.com/html-minifier/)
    * 🛠 [Онлайн-компрессор HTML](http://refresh-sf.com)
    * 📖 [Эксперименты с минификатором HTML — Perfection Kills](http://perfectionkills.com/experimenting-with-html-minifier/#use_short_doctype)
   
- [ ] **Размещайте теги CSS всегда перед тегами JavaScript:** ![high] Убедитесь, что ваш CSS всегда загружается до кода JavaScript.

    ```html
    <!-- Not recommended -->
    <script src="jquery.js"></script>
    <script src="foo.js"></script>
    <link rel="stylesheet" href="foo.css"/>

    <!-- Рекомендуем -->
    <link rel="stylesheet" href="foo.css"/>
    <script src="jquery.js"></script>
    <script src="foo.js"></script>
    ```

    *Почему:*
    > Наличие тегов CSS перед JavaScript обеспечивает лучшую, параллельную загрузку, которая ускоряет время рендеринга в браузере.

    *Как:*
    > ⁃ Убедитесь, что `<link>` и `<style>` в вашем `<head>` всегда находятся перед `<script>`.

    * 📖 [Упорядочивание стилей и скриптов для повышения скорости страниц](https://varvy.com/pagespeed/style-script-order.html)

- [ ] **Минимизируйте количество iframes:** ![high] Используйте iframes только в том случае, если у вас нет другой технической возможности. Старайтесь избегать iframes как можно чаще.

- [ ] **Оптимизация предварительной загрузки с помощью prefetch, dns-prefetch и prerender:** ![low] Популярные браузеры могут использовать директиву в теге `<link>` и атрибут "rel" с определенными ключевыми словами для предварительной загрузки определенных URL.

    *Почему:*
    > Предварительная выборка позволяет браузеру в тихом режиме получать необходимые ресурсы для отображения контента, к которому пользователь может обратиться в ближайшем будущем. Браузер может хранить эти ресурсы в своем кэше и ускорять загрузку веб-страниц, когда они используют разные домены для ресурсов страницы. Когда загрузка веб-страницы завершена и время простоя истекло, браузер начинает загрузку других ресурсов. Когда пользователь переходит по определенной ссылке (уже предварительно сохраненной), контент будет мгновенно предоставлен.

    *Как:*
    > ⁃ Убедитесь, что `<link>` находится в разделе `<head>`.

    * 📖 [Что такое префетчинг и зачем его использовать](https://www.keycdn.com/support/prefetching)
    * 📖 [Предварительная выборка, предварительная загрузка, предварительный просмотр](https://css-tricks.com/prefetching-preloading-prebrowsing/)
    * 📖 [Что такое предварительная загрузка, предварительная выборка и предварительное подключение](https://www.keycdn.com/blog/resource-hints)

**[⬆ back to top](#html)**

## CSS

![css]

- [ ] **Minification:** ![high] All CSS files are minified, comments, white spaces and new lines are removed from production files.

    *Почему:*
    > When CSS files are minified, the content is loaded faster and less data is sent to the client. It's important to always minify CSS files in production. It is beneficial for the user as it is for any business who wants to lower bandwidth costs and lower resource usage.

    *Как:*
    > ⁃ Use tools to minify your files automatically before or during your build or your deployment.

    * 🛠 [cssnano: A modular minifier based on the PostCSS ecosystem. - cssnano](https://cssnano.co/)
    * 🛠 [CSS Minfier](https://goonlinetools.com/css-minifier/)
    * 🛠 [@neutrinojs/style-minify - npm](https://www.npmjs.com/package/@neutrinojs/style-minify)
    * 🛠 [Online CSS Compressor](http://refresh-sf.com)


- [ ] **Concatenation:** ![medium] CSS files are concatenated in a single file *(Not always valid for HTTP/2)*.

    ```html

    <!-- Not recommended -->
    <link rel="stylesheet" href="foo.css"/>
    <link rel="stylesheet" href="bar.css"/>

    <!-- Рекомендуем -->
    <link rel="stylesheet" href="foobar.css"/>
    ```

    *Почему:*
    > If you are still using HTTP/1, you may need to still concatenate your files, it's less true if your server use HTTP/2 (tests should be made).

    *Как:*
    > ⁃ Use online tool or any plugin before or during your build or your deployment to concatenate your files. <br>
    ⁃ Ensure, of course, that concatenation does not break your project.

    * 📖 [HTTP: Optimizing Application Delivery - High Performance Browser Networking (O'Reilly)](https://hpbn.co/optimizing-application-delivery/#optimizing-for-http2)
    * 📖 [Performance Best Practices in the HTTP/2 Era](https://deliciousbrains.com/performance-best-practices-http2/)

- [ ] **Non-blocking:** ![high] CSS files need to be non-blocking to prevent the DOM from taking time to load.

    ```html
    <link rel="preload" href="global.min.css" as="style" onload="this.rel='stylesheet'">
    <noscript><link rel="stylesheet" href="global.min.css"></noscript>
    ```

    *Почему:*
    > CSS files can block the page load and delay the rendering of your page. Using `preload` can actually load the CSS files before the browser starts showing the content of the page.

    *Как:*
    > ⁃ You need to add the `rel` attribute with the `preload` value and add `as="style"` on the `<link>` element.

    * 🛠 [loadCSS by filament group](https://github.com/filamentgroup/loadCSS)
    * 📖 [Example of preload CSS using loadCSS](https://gist.github.com/thedaviddias/c24763b82b9991e53928e66a0bafc9bf)
    * 📖 [Preloading content with rel="preload"](https://developer.mozilla.org/en-US/docs/Web/HTML/Preloading_content)
    * 📖 [Preload: What Is It Good For? — Smashing Magazine](https://www.smashingmagazine.com/2016/02/preload-what-is-it-good-for/)

- [ ] **Unused CSS:** ![medium] Remove unused CSS selectors.

    *Почему:*
    > Removing unused CSS selectors can reduce the size of your files and then speed up the load of your assets.

    *Как:*
    > ⁃ ⚠️ Always check if the framework CSS you want to use don't already has a reset / normalize code included. Sometimes you may not need everything that is inside your reset / normalize file.

    * 🛠 [UnCSS Online](https://uncss-online.com/)
    * 🛠 [PurifyCSS](https://github.com/purifycss/purifycss)
    * 🛠 [PurgeCSS](https://github.com/FullHuman/purgecss)
    * 🛠 [Chrome DevTools Coverage](https://developers.google.com/web/updates/2017/04/devtools-release-notes#coverage)

* [ ] **CSS Critical:** ![high] The CSS critical (or "above the fold") collects all the CSS used to render the visible portion of the page. It is embedded before your principal CSS call and between `<style></style>` in a single line (minified if possible).

    *Почему:*
    > Inlining critical CSS help to speed up the rendering of the web pages reducing the number of requests to the server.

    *Как:*
    > Generate the CSS critical with online tools or using a plugin like the one that Addy Osmani developed.

    * 📖 [Understanding Critical CSS](https://www.smashingmagazine.com/2015/08/understanding-critical-css/)
    * 🛠 [Critical by Addy Osmani on GitHub](https://github.com/addyosmani/critical) automates this.
    * 📖 [Inlining critical CSS for better web performance | Go Make Things](https://gomakethings.com/inlining-critical-css-for-better-web-performance/)
     * 🛠 [Critical Path CSS Generator - Prioritize above the fold content :: SiteLocity](https://www.sitelocity.com/critical-path-css-generator)
     * 📖 [Reduce the size of the above-the-fold content
](https://developers.google.com/speed/docs/insights/PrioritizeVisibleContent)

- [ ] **Embedded or inline CSS:** ![high] Avoid using embed or inline CSS inside your `<body>` *(Not valid for HTTP/2)*

    *Почему:*
    > One of the first reason it's because it's a good practice to **separate content from design**. It also helps you have a more maintainable code and keep your site accessible. But regarding performance, it's simply because it decreases the file-size of your HTML pages and the load time.

    *Как:*
    > Always use external stylesheets or embed CSS in your `<head>` (and follow the others CSS performance rules)

    * 📖 [Observe CSS Best Practices: Avoid CSS Inline Styles](https://www.lifewire.com/avoid-inline-styles-for-css-3466846)

- [ ] **Analyse stylesheets complexity:** ![high] Analyzing your stylesheets can help you to flag issues, redundancies and duplicate CSS selectors.

    *Почему:*
    > Sometimes you may have redundancies or validation errors in your CSS, analysing your CSS files and removed these complexities can help you to speed up your CSS files (because your browser will read them faster)

    *Как:*
    > Your CSS should be organized, using a CSS preprocessor can help you with that. Some online tools listed below can also help you analysing and correct your code.

    * 🛠 [TestMyCSS | Optimize and Check CSS Performance](http://www.testmycss.com/)
    * 🛠 [CSS Stats](https://cssstats.com/)
    * 🛠 [macbre/analyze-css: CSS selectors complexity and performance analyzer](https://github.com/macbre/analyze-css)
    * 🛠 [Project Wallace](https://www.projectwallace.com/) is like CSS Stats but stores stats over time so you can track your changes

**[⬆ back to top](#table-of-contents)**

## Fonts

![fonts]

* 📖 [A Book Apart, Webfont Handbook](https://abookapart.com/products/webfont-handbook)

- [ ] **Webfont formats:** ![medium] You are using WOFF2 on your web project or application.

    *Почему:*
    > According to Google, the WOFF 2.0 Web Font compression format offers 30% average gain over WOFF 1.0. It's then good to use WOFF 2.0, WOFF 1.0 as a fallback and TTF.

    *Как:*
    > Check before buying your new font that the provider gives you the WOFF2 format. If you are using a free font, you can always use Font Squirrel to generate all the formats you need.

    * 📖 [WOFF 2.0 – Learn more about the next generation Web Font Format and convert TTF to WOFF2](https://gist.github.com/sergejmueller/cf6b4f2133bcb3e2f64a)
    * 🛠 [Create Your Own @font-face Kits » Font Squirrel](https://www.fontsquirrel.com/tools/webfont-generator)
    * 🛠 [IcoMoon App - Icon Font, SVG, PDF & PNG Generator](https://icomoon.io/app/)
    * 📖 [Using @font-face | CSS-Tricks](https://css-tricks.com/snippets/css/using-font-face/?ref=frontendchecklist)
    * 📖 [Can I use... WOFF2](https://caniuse.com/#feat=woff2)

- [ ] **Use `preconnect` to load your fonts faster:** ![medium]

    ```html
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    ```

    *Почему:*
    > When you arrived on a website, your device needs to find out where your site lives and which server it needs to connect with. Your browser had to contact a DNS server and wait for the lookup complete before fetching the resource (fonts, CSS files...). Prefetches and preconnects allow the browser to lookup the DNS information and start establishing a TCP connection to the server hosting the font file. This provides a performance boost because by the time the browser gets around to parsing the css file with the font information and discovering it needs to request a font file from the server, it will already have pre-resolved the DNS information and have an open connection to the server ready in its connection pool.

    *Как:*
    > ⁃ Before prefetching your webfonts, use webpagetest to evaluate your website <br>
    ⁃ Look for teal colored DNS lookups and note the host that are being requested <br>
    ⁃ Prefetch your webfonts in your `<head>` and add eventually these hostnames that you should prefetch too

    * 📖 [Faster Google Fonts with Preconnect - CDN Planet](https://www.cdnplanet.com/blog/faster-google-webfonts-preconnect/)
    * 📖 [Make Your Site Faster with Preconnect Hints | Viget](https://www.viget.com/articles/make-your-site-faster-with-preconnect-hints/)
    * 📖 [Ultimate Guide to Browser Hints: Preload, Prefetch, and Preconnect - MachMetrics Speed Blog](https://www.machmetrics.com/speed-blog/guide-to-browser-hints-preload-preconnect-prefetch/)
    * 📖 [A Comprehensive Guide to Font Loading Strategies—zachleat.com](https://www.zachleat.com/web/comprehensive-webfonts/#font-face)
    * 🛠 [typekit/webfontloader: Web Font Loader gives you added control when using linked fonts via @font-face.](https://github.com/typekit/webfontloader)

- [ ] **Webfont size:** ![medium] Webfont sizes don't exceed 300kb (all variants included)

 * 📖 [Font Bytes - Page Weight](https://httparchive.org/reports/page-weight#bytesFont)

- [ ] **Prevent Flash or Invisible Text:** ![medium] Avoid transparent text until the Webfont is loaded

 * 📖 [`font-display` for the Masses](https://css-tricks.com/font-display-masses/)
 * 📖 [CSS font-display: The Future of Font Rendering on the Web](https://www.sitepoint.com/css-font-display-future-font-rendering-web/)

**[⬆ back to top](#table-of-contents)**

## Images

![images]

 * 📖 [Image Bytes in 2018](https://httparchive.org/reports/page-weight#bytesImg)

* [ ] **Images optimization:** ![high] Your images are optimized, compressed without direct impact to the end user.

    *Почему:*
    > Optimized images load faster in your browser and consume less data.

    *Как:*
    > ⁃ Try using CSS3 effects when it's possible (instead of a small image) <br>
    ⁃ When it's possible, use fonts instead of text encoded in your images <br>
    ⁃ Use SVG <br>
    ⁃ Use a tool and specify a level compression under 85.

    * 📖 [Image Optimization | Web Fundamentals | Google Developers](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/image-optimization)
    * 📖 [Essential Image Optimization - An eBook by Addy Osmani](https://images.guide/)
    * 🛠 [TinyJPG – Compress JPEG images intelligently](https://tinyjpg.com/)
    * 🛠 [Kraken.io - Online Image Optimizer](https://kraken.io/web-interface)
    * 🛠 [Compressor.io - optimize and compress JPEG photos and PNG images](https://compressor.io/compress)
    * 🛠 [Cloudinary - Image Analysis Tool](https://webspeedtest.cloudinary.com)
    * 🛠 [ImageEngine - Image Webpage Loading Test](https://demo.imgeng.in)
    * 🛠 [SVGOMG - Optimize SVG vector graphics files](https://jakearchibald.github.io/svgomg/)


* [ ] **Images format:** ![high] Choose your image format appropriately.

    *Почему:*
    > To ensure that your images don't slow your website, choose the format that will correspond to your image. If it's a photo, JPEG is most of the time more appropriate than PNG or GIF. But don't forget to look a the nex-gen formats which can reduce the size of your files. Each image format has pros and cons, it's important to know these to make the best choice possible.

    *Как:*
    > ⁃ Use [Lighthouse](https://developers.google.com/web/tools/lighthouse/) to identify which images can eventually use **next-gen formats** (like JPEG 2000m JPEG XR or WebP) <br>
    ⁃ Compare different formats, sometimes using PNG8 is better than PNG16, sometimes it's not.

    * 📖 [Serve Images in Next-Gen Formats  |  Tools for Web Developers  |  Google Developers](https://developers.google.com/web/tools/lighthouse/audits/webp)
    * 📖 [What Is the Right Image Format for Your Website? — SitePoint](https://www.sitepoint.com/what-is-the-right-image-format-for-your-website/)
    * 📖 [PNG8 - The Clear Winner — SitePoint](https://www.sitepoint.com/png8-the-clear-winner/)
    * 📖 [8-bit vs 16-bit - What Color Depth You Should Use And Why It Matters - DIY Photography](https://www.diyphotography.net/8-bit-vs-16-bit-color-depth-use-matters/)

- [ ] **Use vector image vs raster/bitmap:** ![medium] Prefer using vector image rather than bitmap images (when possible).

    *Почему:*
    > Vector images (SVG) tend to be smaller than images and SVG's are responsive and scale perfectly. These images can be animated and modified by CSS.

* [ ] **Images dimensions:** ![medium] Set `width` and `height` attributes on `<img>` if the final rendered image size is known.

    *Почему:*
    > If height and width are set, the space required for the image is reserved when the page is loaded. However, without these attributes, the browser does not know the size of the image, and cannot reserve the appropriate space to it. The effect will be that the page layout will change during loading (while the images load).

* [ ] **Avoid using Base64 images:** ![medium] You could eventually convert tiny images to base64 but it's actually not the best practice.

    * 📖 [Base64 Encoding & Performance, Part 1 and 2 by Harry Roberts](https://csswizardry.com/2017/02/base64-encoding-and-performance/)
    * 📖 [A closer look at Base64 image performance – The Page Not Found Blog](http://www.andygup.net/a-closer-look-at-base64-image-performance/)
    * 📖 [When to base64 encode images (and when not to) | David Calhoun](https://www.davidbcalhoun.com/2011/when-to-base64-encode-images-and-when-not-to/)
   * 📖 [Base64 encoding images for faster pages | Performance and seo factors](https://varvy.com/pagespeed/base64-images.html)

* [ ] **Lazy loading:** ![medium] Offscreen images are loaded lazily (A noscript fallback is always provided).

    *Почему:*
    > It will improve the response time of the current page and then avoid loading unnecessary images that the user may not need.

    *Как:*
    > ⁃ Use [Lighthouse](https://developers.google.com/web/tools/lighthouse/) to identify how many **images are offscreen**. <br>
    ⁃ Use a JavaScript plugin like the following to lazyload your images. Make sure you target offscreen images only. <br>
    ⁃ Also make sure to lazyload alternative images shown at mouseover or upon other user actions.

    * 🛠 [verlok/lazyload: GitHub](https://github.com/verlok/lazyload)
    * 🛠 [aFarkas/lazysizes: GitHub](https://github.com/aFarkas/lazysizes/)
    * 🛠 [mfranzke/loading-attribute-polyfill: GitHub](https://github.com/mfranzke/loading-attribute-polyfill/)
    * 📖 [Lazy Loading Images and Video  |  Web Fundamentals  |  Google Developers](https://developers.google.com/web/fundamentals/performance/lazy-loading-guidance/images-and-video/)
    * 📖 [5 Brilliant Ways to Lazy Load Images For Faster Page Loads - Dynamic Drive Blog](http://blog.dynamicdrive.com/5-brilliant-ways-to-lazy-load-images-for-faster-page-loads/)

* [ ] **Responsive images:** ![medium] Ensure to serve images that are close to your display size.

    *Почему:*
    > Small devices don't need images bigger than their viewport. It's recommended to have multiple versions of one image on different sizes.

    *Как:*
    > ⁃ Create different image sizes for the devices you want to target. <br>
    ⁃ Use `srcset` and `picture` to deliver multiple variants of each image.

     * 📖 [Responsive images - Learn web development | MDN](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)

**[⬆ back to top](#table-of-contents)**

## JavaScript

![javascript]

- [ ] **JS Minification:** ![high] All JavaScript files are minified, comments, white spaces and new lines are removed from production files *(still valid if using HTTP/2)*.

    *Почему:*
    > Removing all unnecessary spaces, comments and break will reduce the size of your JavaScript files and speed up your site's page load times and obviously lighten the download for your user.

    *Как:*
    > ⁃ Use the tools suggested below to minify your files automatically before or during your build or your deployment.

    * 🛠 [uglify-js - npm](https://www.npmjs.com/package/uglify-js)
    * 🛠 [Online JavaScript Compressor](http://refresh-sf.com)
    * 📖 [Short read: How is HTTP/2 different? Should we still minify and concatenate?](https://scaleyourcode.com/blog/article/28)

* [ ] **No JavaScript inside:** ![medium] *(Only valid for website)* Avoid having multiple JavaScript codes embedded in the middle of your body. Regroup your JavaScript code inside external files or eventually in the `<head>` or at the end of your page (before `</body>`).

    *Почему:*
    > Placing JavaScript embedded code directly in your `<body>` can slow down your page because it loads while the DOM is being built. The best option is to use external files with `async` or `defer` to avoid blocking the DOM. Another option is to place some scripts inside your `<head>`. Most of the time analytics code or small script that need to load before the DOM gets to main processing.

    *Как:*
    > Ensure that all your files are loaded using `async` or `defer` and decide wisely the code that you will need to inject in your `<head>`.

     * 📖 [11 Tips to Optimize JavaScript and Improve Website Loading Speeds](https://www.upwork.com/hiring/development/11-tips-to-optimize-javascript-and-improve-website-loading-speeds/)

* [ ] **Non-blocking JavaScript:** ![high] JavaScript files are loaded asynchronously using `async` or deferred using `defer` attribute.

    ```html
    <!-- Defer Attribute -->
    <script defer src="foo.js"></script>

    <!-- Async Attribute -->
    <script async src="foo.js"></script>
    ```

    *Почему:*
    > JavaScript blocks the normal parsing of the HTML document, so when the parser reaches a `<script>` tag (particularly is inside the `<head>`), it stops to fetch and run it. Adding `async` or `defer` are highly recommended if your scripts are placed in the top of your page but less valuable if just before your `</body>` tag. But it's a good practice to always use these attributes to avoid any performance issue.

    *Как:*
    > ⁃ Add `async` (if the script don't rely on other scripts) or `defer` (if the script relies upon or relied upon by an async script) as an attribute to your script tag. <br>
    ⁃ If you have small scripts, maybe use inline script place above async scripts.

    * 📖 [Remove Render-Blocking JavaScript](https://developers.google.com/speed/docs/insights/BlockingJS)
    * 📖 [Defer loading JavaScript](https://varvy.com/pagespeed/defer-loading-javascript.html)

* [ ] **Optimized and updated JS libraries:** ![medium] All JavaScript libraries used in your project are necessary (prefer Vanilla JavaScript for simple functionalities), updated to their latest version and don't overwhelm your JavaScript with unnecessary methods.

    *Почему:*
    > Most of the time, new versions come with optimization and security fix. You should use the most optimized code to speed up your project and ensure that you'll not slow down your website or app without outdated plugin.

    *Как:*
    > If your project use NPM packages, [npm-check](https://www.npmjs.com/package/npm-check) is a pretty interesting library to upgrade / update your libraries.
    > [Greenkeeper](https://greenkeeper.io/) can automatically look for your dependencies and suggest an update every time a new version is out.

    * 📖 [You may not need jQuery](http://youmightnotneedjquery.com/)
    * 📖 [Vanilla JavaScript for building powerful web applications](https://plainjs.com/)

- [ ] **Check dependencies size limit:** ![low] Ensure to use wisely external libraries, most of the time, you can use a lighter library for a same functionality.

    *Почему:*
    > You may be tempted to use one of the 745 000 packages you can find on [npm](https://www.npmjs.com/), but you need to choose the best package for your needs. For example, MomentJS is an awesome library but with a lot of methods you may never use, that's why Day.js was created. It's just 2kB vs 16.4kB gz for Moment.

    *Как:*
    > Always compare and choose the best and lighter library for your needs. You can also use tools like [npm trends](http://www.npmtrends.com/) to compare NPM package downloads counts or [Bundlephobia](https://bundlephobia.com/) to know the size of your dependencies.

    * 🛠 [ai/size-limit: Prevent JS libraries bloat. If you accidentally add a massive dependency, Size Limit will throw an error.](https://github.com/ai/size-limit)
    * 🛠 [webpack-bundle-analyzer - npm](https://www.npmjs.com/package/webpack-bundle-analyzer)
    * 🛠 [js-dependency-viewer - npm](https://www.npmjs.com/package/js-dependency-viewer)
    * 📖 [Size Limit: Make the Web lighter — Martian Chronicles, Evil Martians’ team blog](https://evilmartians.com/chronicles/size-limit-make-the-web-lighter)

- [ ] **JavaScript Profiling:** ![medium] Check for performance problems in your JavaScript files (and CSS too).

    *Почему:*
    > JavaScript complexity can slow down runtime performance. Identifying these possible issues are essential to offer the smoothest user experience.

    *Как:*
    > Use the Timeline tool in the Chrome Developer Tool to evaluate scripts events and found the one that may take too much time.

     * 📖 [Speed Up JavaScript Execution  |  Tools for Web Developers  |  Google Developers](https://developers.google.com/web/tools/chrome-devtools/rendering-tools/js-execution)
    * 📖 [JavaScript Profiling With The Chrome Developer Tools — Smashing Magazine](https://www.smashingmagazine.com/2012/06/javascript-profiling-chrome-developer-tools/)
    * 📖 [How to Record Heap Snapshots  |  Tools for Web Developers  |  Google Developers](https://developers.google.com/web/tools/chrome-devtools/memory-problems/heap-snapshots)
    * 📖 [Chapter 22 - Profiling the Frontend - Blackfire](https://blackfire.io/docs/book/22-frontend-profiling)
    * 📖 [30 Tips To Improve Javascript Performance](http://www.monitis.com/blog/30-tips-to-improve-javascript-performance/)

- [ ] **Use of Service Workers:** ![medium] You are using Service Workers in your PWA to cache data or execute possible heavy tasks without impacting the user experience of your application.
   
    * 📖 [Service Workers: an Introduction  |  Web Fundamentals  |  Google Developers](https://developers.google.com/web/fundamentals/primers/service-workers/)
    * 📖 [Measuring the Real-world Performance Impact of Service Workers  |  Web  |  Google Developers](https://developers.google.com/web/showcase/2016/service-worker-perf)
    * 📖 [What Are Service Workers and How They Help Improve Performance](https://www.keycdn.com/blog/service-workers/)
    * 📹 [How does a service worker work? - YouTube](https://www.youtube.com/watch?v=__xAtWgfzvc)

**[⬆ back to top](#table-of-contents)**

## Server

![server-side]

- [ ] **Your website is using HTTPS:** ![high]

    *Почему:*
    > HTTPS is not only for ecommerce websites, but for all websites that are exchanging data. Data shared by a user or data shared to an external entity. Modern browsers today limit functionalities for sites that are not secure. For example: geolocation, push notifications and service workers don't work if your instance is not using HTTPS. And today is much more easy to setup a project with an SSL certificate than it was before (and for free, thanks to [Let's Encrypt](https://letsencrypt.org/)).

 * 📖 [Why Use HTTPS? | Cloudflare](https://www.cloudflare.com/learning/security/why-use-https/)
 * 📖 [Enabling HTTPS Without Sacrificing Your Web Performance - Moz](https://moz.com/blog/enabling-https-without-sacrificing-web-performance)
 * 📖 [How HTTPS Affects Website Performance](https://wp-rocket.me/blog/https-affects-website-performance/)
 * 📖 [HTTP versus HTTPS versus HTTP2 - The real story | Tune The Web](https://www.tunetheweb.com/blog/http-versus-https-versus-http2/)
 * 📖 [HTTP vs HTTPS — Test them both yourself](https://www.httpvshttps.com/)

- [ ] **Page weight < 1500 KB (ideally < 500 KB):** ![high] Reduce the size of your page + resources as much as you can.

    *Почему:*
    > Ideally you should try to target < 500 KB but the state of web shows that the median of Kilobytes is around 1500 KB (even on mobile). Depending on your target users, network connection, devices, it's important to reduce as much as possible your total Kilobytes to have the best user experience possible.

    *Как:*
    > ⁃ All the rules inside the Front-End Performance Checklist will help you to reduce as much as possible your resources and your code.

    * 📖 [Page Weight](https://httparchive.org/reports/page-weight#bytesTotal)
    * 🛠 [What Does My Site Cost?](https://whatdoesmysitecost.com/)
    * 🛠 [web - Measure full page size in Chrome DevTools - Stack Overflow](https://stackoverflow.com/questions/38239980/measure-full-page-size-in-chrome-devtools)

- [ ] **Page load times < 3 seconds:** ![high] Reduce as much as possible your page load times to quickly deliver your content to your users.

    *Почему:*
    > Faster your website or app is, less you have probability of bounce increases, in other terms you have less chances to lose your user or future client. Enough researches on the subject prove that point.

    *Как:*
    > Use online tools like [Page Speed Insight](https://developers.google.com/speed/pagespeed/insights/) or [WebPageTest](https://www.webpagetest.org/) to analyze what could be slowing you down and use the Front-End Performance Checklist to improve your load times.

    * 🛠 [Compare your mobile site speed](https://www.thinkwithgoogle.com/feature/mobile/)
    * 🛠 [Test Your Mobile Website Speed and Performance - Think With Google](https://testmysite.thinkwithgoogle.com/intl/en-us)
    * 📖 [Average Page Load Times for 2018 - How does yours compare? - MachMetrics Speed Blog](https://www.machmetrics.com/speed-blog/average-page-load-times-websites-2018/)

- [ ] **Time To First Byte < 1.3 seconds:** ![high] Reduce as much as you can the time your browser waits before receiving data.

    * 📖 [What is Waiting (TTFB) in DevTools, and what to do about it](https://scaleyourcode.com/blog/article/27)
    * 📖 [Monitoring your servers with free tools is easy](https://scaleyourcode.com/blog/article/7)
    * 📖 [Time to First Byte (TTFB)](https://varvy.com/pagespeed/ttfb.html)
    * 🛠 [Global latency testing tool](https://latency.apex.sh)

* [ ] **Cookie size:** ![medium] If you are using cookies, be sure each cookie doesn't exceed 4096 bytes and your domain name doesn't have more than 20 cookies.

    *Почему:*
    > Cookies are exchanged in the HTTP headers between web servers and browsers. It's important to keep the size of cookies as low as possible to minimize the impact on the user's response time.

    *Как:*
    > Eliminate unnecessary cookies.

    * 📖 [Cookie specification: RFC 6265](https://tools.ietf.org/html/rfc6265)
    * 📖 [Cookies](https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies)
    * 🛠 [Browser Cookie Limits](http://browsercookielimits.squawky.net/)
    * 📖 [Website Performance: Cookies Don't Taste So Good - Monitis Blog](http://www.monitis.com/blog/website-performance-cookies-dont-taste-so-good/)
    * 📖 [Google's Web Performance Best Practices #3: Minimize Request Overhead - GlobalDots Blog](https://www.globaldots.com/googles-web-performance-best-practices-3-minimize-request-overhead/)

- [ ] **Minimizing HTTP requests:** ![high] Always ensure that every file requested are essential for your website or application.
 * 📖 [Combine external CSS](https://varvy.com/pagespeed/combine-external-css.html)
 * 📖 [Combine external JavaScript](https://varvy.com/pagespeed/combine-external-javascript.html)

- [ ] **Use a CDN to deliver your assets:** ![medium] Use a CDN to deliver faster your content over the world.

 * 📖 [10 Tips to Optimize CDN Performance - CDN Planet](https://www.cdnplanet.com/blog/10-tips-optimize-cdn-performance/)
 * 📖 [HTTP Caching  |  Web Fundamentals  |  Google Developers](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/http-caching)

- [ ] **Serve files from the same protocol:** ![high] Avoid having your website serving files coming from source using HTTP on your website which is using HTTPS for example. If your website is using HTTPS, external files should come from the same protocol.

- [ ] **Serve reachable files:** ![high] Avoid requesting unreachable files (404).
 * 📖 [How to avoid bad requests](https://varvy.com/pagespeed/avoid-bad-requests.html)

- [ ] **Set HTTP cache headers properly:** ![high] Set HTTP headers to avoid expensive number of roundtrips between your browser and the server.
 * 📖 [Using cache-control for browser caching](https://varvy.com/pagespeed/cache-control.html)

- [ ] **GZIP / Brotli compression is enabled:** ![high] Use a compression method such as Gzip or Brotli to reduce the size of your JavaScript files. With a smaller sizes file, users will be able to download the asset faster, resulting in improved performance.

 * 🛠 [Check GZIP compression](https://checkgzipcompression.com/)
 * 🛠 [Check Brotli Compression](https://tools.keycdn.com/brotli-test)
 * 📖 [Can I use... Brotli](https://caniuse.com/#feat=brotli)

**[⬆ back to top](#table-of-contents)**

---
## Performances and JS Frameworks

### Angular
 * 📖 [Angular Performance Checklist](https://github.com/mgechev/angular-performance-checklist)

### React

 * 📖 [Optimizing Performance - React](https://reactjs.org/docs/optimizing-performance.html)
 * 📖 [React image manipulation | Cloudinary](https://cloudinary.com/documentation/react_image_manipulation)
 * 📖 [Debugging React performance with React 16 and Chrome Devtools.](https://building.calibreapp.com/debugging-react-performance-with-react-16-and-chrome-devtools-c90698a522ad)
  * 📖 [Build Performant - React](https://web.dev/react/)

### Vue
 * 📖 [Vue - Useful Links|Style Guide and Performance](https://learn-vuejs.github.io/vue-patterns/useful-links/)

## Performances and CMS

### WordPress

* 🛠 [Test Your Website Speed | WordPress Hosting by @WPEngine](https://wpengine.com/speed-tool/)

#### Articles

 * 📖 [19 Tips to Speed Up WordPress Performance (Updated)](https://www.wpbeginner.com/wordpress-performance-speed/)
 * 📖 [Speed Up Your WordPress - How to Save Images Optimized for Web](https://www.wpbeginner.com/beginners-guide/speed-wordpress-save-images-optimized-web/)

#### Plugins recommended

* 🛠 [Caching Plugin for WordPress - Speed up your website with WP Rocket](https://wp-rocket.me/)
* 🛠 [WP-Sweep | WordPress.org](https://wordpress.org/plugins/wp-sweep/)
* 🛠 [Imagify Image Optimizer | WordPress.org](https://wordpress.org/plugins/imagify/)

---

## Translations

The Front-End Performance Checklist wants to also be available in other languages! Don't hesitate to submit your contribution!

* 🇵🇹 Portuguese: [fernandofawkes/Front-End-Performance-Checklist](https://github.com/fernandofawkes/Front-End-Performance-Checklist)
* 🇨🇳 Chinese: [JohnsenZhou/Front-End-Performance-Checklist](https://github.com/JohnsenZhou/Front-End-Performance-Checklist)
* 🇷🇺 Russian: [lex111/Front-End-Performance-Checklist](https://github.com/lex111/Front-End-Performance-Checklist)
* 🇫🇷 French: [WilliamDASILVA/Front-End-Performance-Checklist](https://github.com/WilliamDASILVA/Front-End-Performance-Checklist)
* 🇰🇷 Korean: [ParkSB/Front-End-Performance-Checklist](https://github.com/ParkSB/Front-End-Performance-Checklist)
* 🇪🇸 Spanish: [dagerzuga/Front-End-Performance-Checklist](https://github.com/dagerzuga/Front-End-Performance-Checklist)
* 🇻🇳 Vietnamese : [huynhan147/Front-End-Performance-Checklist](https://github.com/huynhan147/FrontEnd-Performance-Checklist)
* 🇯🇵 Japanese: [GameWith/Front-End-Performance-Checklist](https://github.com/GameWith/Front-End-Performance-Checklist)
* 🇵🇱 Polish: [mbiesiad/Front-End-Performance-Checklist](https://github.com/mbiesiad/Front-End-Performance-Checklist)
* 🇮🇷 Persian: [ms-fadaei/Front-End-Performance-Checklist](https://github.com/ms-fadaei/Front-End-Performance-Checklist)
* 🇮🇹 Italian: [marbio/Front-End-Performance-Checklist](https://github.com/marbio/Front-End-Performance-Checklist)

## Contributing

**Open an issue or a pull request to suggest changes or additions.**

## Support

If you have any question or suggestion, don't hesitate to use Discord or Twitter:

* [Chat on Discord](https://discord.gg/btHQRkm)
* [Facebook](https://www.facebook.com/frontendchecklist/)
* [Twitter](https://twitter.com/thedaviddias)

## Author

**Build with ❤️ by [David Dias](https://github.com/thedaviddias)

## Contributors

This project exists thanks to all the people who contribute. [[Contribute]](.github/CONTRIBUTING.md).
<a href="https://github.com/thedaviddias/Front-End-Performance-Checklist/graphs/contributors">
    <img src="https://opencollective.com/front-end-checklist/contributors.svg?width=890" />
</a>


## Backers

Thank you to all our backers! 🙏 [[Become a backer](https://opencollective.com/front-end-checklist#backer)]

<a href="https://opencollective.com/front-end-checklist#backers" target="_blank"><img src="https://opencollective.com/front-end-checklist/backers.svg?width=890"></a>


## Sponsors

Support this project by becoming a sponsor. Your logo will show up here with a link to your website. [[Become a sponsor](https://opencollective.com/front-end-checklist#sponsor)]

<a href="https://opencollective.com/front-end-checklist/sponsor/0/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/0/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/1/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/1/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/2/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/2/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/3/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/3/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/4/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/4/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/5/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/5/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/6/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/6/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/7/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/7/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/8/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/8/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/9/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/9/avatar.svg"></a>

## License

[MIT](LICENSE)

All icons are provided by [Icons8](https://icons8.com/)

**[⬆ back to top](#table-of-contents)**

[logo]: images/logo-front-end-performance-checklist.jpg
[html]: images/html.png
[css]: images/css.png
[fonts]: images/fonts.png
[images]: images/images.png
[javascript]: images/javascript.png
[server-side]: images/server-side.png

[low]: images/priority/low.svg
[medium]: images/priority/medium.svg
[high]: images/priority/high.svg
