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
    <!-- Не рекомендуется -->
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

- [ ] **Минификация:** ![high] Все CSS-файлы минифицированы, комментарии, пробелы и новые строки удалены из рабочих файлов.

    *Почему:*
    > Когда CSS-файлы минифицированы, содержимое загружается быстрее, а клиенту отправляется меньше данных. Важно всегда минифицировать CSS-файлы в производстве. Это полезно как для пользователя, так и для любого предприятия, которое хочет снизить затраты на пропускную способность и уменьшить использование ресурсов.

    *Как:*
    > ⁃ Используйте инструменты для автоматического минимизации файлов до или во время сборки или развертывания.

    * 🛠 [cssnano: Модульный минификатор, основанный на экосистеме PostCSS. - cssnano](https://cssnano.co/)
    * 🛠 [CSS Minfier](https://goonlinetools.com/css-minifier/)
    * 🛠 [@neutrinojs/style-minify - npm](https://www.npmjs.com/package/@neutrinojs/style-minify)
    * 🛠 [Online CSS Compressor](http://refresh-sf.com)


- [ ] **Конкатенация:** ![medium] Файлы CSS объединяются в один файл *(Не всегда подходит для HTTP/2)*.

    ```html

    <!-- Не рекомендуется -->
    <link rel="stylesheet" href="foo.css"/>
    <link rel="stylesheet" href="bar.css"/>

    <!-- Рекомендуем -->
    <link rel="stylesheet" href="foobar.css"/>
    ```

    *Почему:*
    > Если вы все еще используете HTTP/1, вам может потребоваться конкатенация файлов, это менее верно, если ваш сервер использует HTTP/2 (необходимо провести тестирование).

    *Как:*
    > ⁃ Используйте онлайн-инструмент или любой плагин до или во время сборки или развертывания для конкатенации файлов. <br>
    ⁃ Конечно, убедитесь, что конкатенация не разрушит ваш проект.

    * 📖 [HTTP: Оптимизация доставки приложений - высокопроизводительные браузерные сети (O'Reilly)](https://hpbn.co/optimizing-application-delivery/#optimizing-for-http2)
    * 📖 [Лучшие практики производительности в эпоху HTTP/2](https://deliciousbrains.com/performance-best-practices-http2/)

- [ ] **Неблокируемый:** ![high] Файлы CSS должны быть неблокируемыми, чтобы DOM не тратил время на загрузку.

    ```html
    <link rel="preload" href="global.min.css" as="style" onload="this.rel='stylesheet'">
    <noscript><link rel="stylesheet" href="global.min.css"></noscript>
    ```

    *Почему:*
    > Файлы CSS могут блокировать загрузку страницы и задерживать ее отображение. Использование `preload` может фактически загрузить CSS-файлы до того, как браузер начнет отображать содержимое страницы.

    *Как:*
    > ⁃ Вам нужно добавить атрибут `rel` со значением `preload` и добавить `as="style"` на элемент `<link>`..

    * 🛠 [loadCSS от filament group](https://github.com/filamentgroup/loadCSS)
    * 📖 [Пример предварительной загрузки CSS с помощью loadCSS](https://gist.github.com/thedaviddias/c24763b82b9991e53928e66a0bafc9bf)
    * 📖 [Предварительная загрузка содержимого с помощью rel="preload"](https://developer.mozilla.org/en-US/docs/Web/HTML/Preloading_content)
    * 📖 [Предварительная нагрузка: Для чего она нужна? — Smashing Magazine](https://www.smashingmagazine.com/2016/02/preload-what-is-it-good-for/)

- [ ] **Неиспользуемый CSS:** ![medium] Удаление неиспользуемых селекторов CSS.

    *Почему:*
    > Удаление неиспользуемых CSS-селекторов позволяет уменьшить размер файлов и ускорить загрузку активов..

    *Как:*
    > ⁃ ⚠️ Всегда проверяйте, нет ли в CSS фреймворка, который вы хотите использовать, уже включенного кода сброса / нормализации. Иногда вам может не понадобиться все, что находится в файле reset / normalize.

    * 🛠 [UnCSS Online](https://uncss-online.com/)
    * 🛠 [PurifyCSS](https://github.com/purifycss/purifycss)
    * 🛠 [PurgeCSS](https://github.com/FullHuman/purgecss)
    * 🛠 [Chrome DevTools Coverage](https://developers.google.com/web/updates/2017/04/devtools-release-notes#coverage)

* [ ] **CSS Critical:** ![high] Критический CSS собирает все CSS, используемые для отображения видимой части страницы. Он встраивается перед основным вызовом CSS и между `<style></style>` в одну строку (по возможности минифицированную).

    *Почему:*
    > Встраивание критических CSS помогает ускорить рендеринг веб-страниц, уменьшая количество запросов к серверу.

    *Как:*
    > Создайте критический CSS с помощью онлайн-инструментов или используя плагин, подобный тому, который разработал Адди Османи..

    * 📖 [Понимание критических CSS](https://www.smashingmagazine.com/2015/08/understanding-critical-css/)
    * 🛠 [Critical by Addy Osmani on GitHub](https://github.com/addyosmani/critical) automates this.
    * 📖 [Инкрустация критических CSS для повышения производительности сайта | Go Make Things](https://gomakethings.com/inlining-critical-css-for-better-web-performance/)
    * 🛠 [Генератор CSS Critical Path - приоритет контента :: SiteLocity](https://www.sitelocity.com/critical-path-css-generator)
    * 📖 [Уменьшите размер контента, расположенного выше страницы.](https://developers.google.com/speed/docs/insights/PrioritizeVisibleContent)

- [ ] **Встроенный или инлайн CSS:** ![high] Избегайте использования встроенного или инлайн CSS внутри вашего `<body>` *(Недействительно для HTTP/2).*

    *Почему:*
    > Одна из первых причин заключается в том, что это хорошая практика - **отделять контент от дизайна**. Это также поможет вам иметь более удобный код и сохранить доступность вашего сайта. Что касается производительности, то это просто потому, что это уменьшает размер файла HTML-страниц и время загрузки..

    *Как:*
    > Всегда используйте внешние таблицы стилей или вставляйте CSS в `<head>` (и следуйте другим правилам работы с CSS).

    * 📖 [Соблюдайте лучшие практики CSS: Избегайте инлайн-стилей CSS](https://www.lifewire.com/avoid-inline-styles-for-css-3466846)

- [ ] **Анализ сложности таблиц стилей:** ![high] Анализ таблиц стилей поможет вам выявить проблемы, излишества и дублирование CSS-селекторов..

    *Почему:*
    > Иногда в вашем CSS могут быть излишества или ошибки валидации. Анализ ваших CSS-файлов и устранение этих сложностей может помочь вам ускорить работу ваших CSS-файлов (потому что браузер будет читать их быстрее).

    *Как:*
    > Ваш CSS должен быть организован, в этом вам поможет использование препроцессора CSS. Некоторые онлайн-инструменты, перечисленные ниже, также могут помочь вам проанализировать и исправить ваш код.

    * 🛠 [TestMyCSS | Оптимизация и проверка производительности CSS](http://www.testmycss.com/)
    * 🛠 [CSS Stats](https://cssstats.com/)
    * 🛠 [macbre/analyze-css: Анализатор сложности и производительности CSS-селекторов](https://github.com/macbre/analyze-css)
    * 🛠 [Проект "Уоллес"](https://www.projectwallace.com/) is like CSS Stats but stores stats over time so you can track your changes

**[⬆ back to top](#css)**

## Шрифты

![fonts]

* 📖 [A Book Apart, Webfont Handbook](https://abookapart.com/products/webfont-handbook)

- [ ] **Форматы веб-шрифтов:** ![medium] Вы используете WOFF2 в своем веб-проекте или приложении.

    *Почему:*
    > По данным Google, формат сжатия веб-шрифтов WOFF 2.0 в среднем на 30 % превосходит WOFF 1.0. Поэтому целесообразно использовать WOFF 2.0, WOFF 1.0 в качестве запасного варианта и TTF.

    *Как:*
    > Перед покупкой нового шрифта убедитесь, что поставщик предоставляет вам формат WOFF2. Если вы используете бесплатный шрифт, вы всегда можете использовать Font Squirrel для создания всех необходимых форматов.

    * 📖 [WOFF 2.0 – Узнайте больше о новом поколении формата веб-шрифтов и конвертируйте TTF в WOFF2](https://gist.github.com/sergejmueller/cf6b4f2133bcb3e2f64a) 
    * 🛠 [IcoMoon App - Icon Font, SVG, PDF & PNG Generator](https://icomoon.io/app/)
    * 📖 [Using @font-face | CSS-Tricks](https://css-tricks.com/snippets/css/using-font-face/?ref=frontendchecklist)
    * 📖 [Can I use... WOFF2](https://caniuse.com/#feat=woff2)

- [ ] **Используйте `preconnect` для более быстрой загрузки шрифтов:** ![medium]

    ```html
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    ```

    *Почему:*
    > Когда вы зашли на веб-сайт, вашему устройству необходимо выяснить, где находится сайт и с каким сервером ему нужно соединиться. Ваш браузер должен был связаться с DNS-сервером и дождаться завершения поиска, прежде чем получить ресурс (шрифты, CSS-файлы...). Префетчи и преконнекты позволяют браузеру просмотреть информацию DNS и начать устанавливать TCP-соединение с сервером, на котором находится файл шрифта. Это повышает производительность, поскольку к тому времени, когда браузер разберет css-файл с информацией о шрифте и обнаружит, что ему нужно запросить файл шрифта у сервера, он уже предварительно разрешит DNS-информацию и будет иметь открытое соединение с сервером в своем пуле соединений.

    *Как:*
    > ⁃ Перед предварительной выборкой веб-шрифтов используйте webpagetest для оценки вашего сайта <br>
    ⁃ Найдите DNS-поиск, окрашенный в тиловый цвет, и обратите внимание на хост, который запрашивается <br>
    ⁃ Предварительная выборка веб-шрифтов в вашем `<head>` и добавьте в конце концов эти имена хостов, которые вы тоже должны предварительно выбрать

    * 📖 [Более быстрые шрифты Google с помощью Preconnect - CDN Planet](https://www.cdnplanet.com/blog/faster-google-webfonts-preconnect/)
    * 📖 [Сделайте свой сайт быстрее с помощью подсказок Preconnect | Viget](https://www.viget.com/articles/make-your-site-faster-with-preconnect-hints/)
    * 📖 [Полное руководство по подсказкам браузера: Предварительная загрузка, предварительная выборка и предварительное подключение - MachMetrics Speed Blog](https://www.machmetrics.com/speed-blog/guide-to-browser-hints-preload-preconnect-prefetch/)
    * 📖 [Исчерпывающее руководство по стратегиям загрузки шрифтов — zachleat.com](https://www.zachleat.com/web/comprehensive-webfonts/#font-face)
    * 🛠 [typekit/webfontloader: Web Font Loader обеспечивает дополнительный контроль при использовании связанных шрифтов через @font-face.](https://github.com/typekit/webfontloader)

- [ ] **Размер веб-шрифта:** ![medium] Размер веб-шрифта не должен превышать 300 кб (все варианты включены)

 * 📖 [Байт шрифта - Вес страницы](https://httparchive.org/reports/page-weight#bytesFont)

- [ ] **Предотвращение флэш- или невидимого текста:** ![medium] Избегайте прозрачного текста, пока не загрузится веб-шрифт

 * 📖 [`font-display` для масс ](https://css-tricks.com/font-display-masses/)
 * 📖 [CSS font-display: Будущее рендеринга шрифтов в Интернете](https://www.sitepoint.com/css-font-display-future-font-rendering-web/)

**[⬆ back to top](#шрифты)**

## Изображения

![images]

 * 📖 [Image Bytes in 2018](https://httparchive.org/reports/page-weight#bytesImg)

* [ ] **Оптимизация изображений:** ![high] Ваши изображения оптимизированы, сжаты без прямого воздействия на конечного пользователя.

    *Почему:*
    > Оптимизированные изображения быстрее загружаются в браузере и потребляют меньше данных.

    *Как:*
    > ⁃ Попробуйте использовать эффекты CSS3, когда это возможно (вместо маленького изображения). <br>
    ⁃ Если это возможно, используйте шрифты вместо текста, закодированного в изображениях. <br>
    ⁃ Используйте SVG <br>
    ⁃ Используйте инструмент и задайте уровень сжатия ниже 85.

    * 📖 [Image Optimization | Web Fundamentals | Google Developers](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/image-optimization)
    * 📖 [Важнейшая оптимизация изображений - An eBook by Addy Osmani](https://images.guide/)
    * 🛠 [TinyJPG – Интеллектуальное сжатие изображений JPEG](https://tinyjpg.com/)
    * 🛠 [Kraken.io - Онлайн-оптимизатор изображений](https://kraken.io/web-interface)
    * 🛠 [Compressor.io - оптимизация и сжатие фотографий JPEG и изображений PNG](https://compressor.io/compress)
    * 🛠 [Cloudinary - Инструмент для анализа изображений](https://webspeedtest.cloudinary.com)
    * 🛠 [ImageEngine - Тест загрузки веб-страниц с изображениями](https://demo.imgeng.in)
    * 🛠 [SVGOMG - Оптимизация файлов векторной графики SVG](https://jakearchibald.github.io/svgomg/)


* [ ] **Формат изображений:** ![high] Выберите подходящий формат изображения.

    *Почему:*
    > Чтобы изображения не тормозили работу сайта, выберите формат, который будет соответствовать вашему изображению. Если это фотография, то JPEG чаще всего подходит больше, чем PNG или GIF. Но не забудьте обратить внимание на некст-ген форматы, которые могут уменьшить размер файлов. У каждого формата изображений есть плюсы и минусы, и важно знать их, чтобы сделать наилучший выбор.

    *Как:*
    > ⁃ Используйте [Lighthouse](https://developers.google.com/web/tools/lighthouse/) чтобы определить, какие изображения могут использовать **форматы следующего поколения** (например, JPEG 2000m JPEG XR или WebP). <br>
    ⁃ Сравните разные форматы, иногда использование PNG8 лучше PNG16, иногда нет.

    * 📖 [Подача изображений в форматах нового поколения  |  Tools for Web Developers  |  Google Developers](https://developers.google.com/web/tools/lighthouse/audits/webp)
    * 📖 [Какой формат изображений подходит для вашего сайта? — SitePoint](https://www.sitepoint.com/what-is-the-right-image-format-for-your-website/)
    * 📖 [PNG8 - Явный победитель — SitePoint](https://www.sitepoint.com/png8-the-clear-winner/)
    * 📖 [8-bit vs 16-bit - Какую глубину цвета следует использовать и почему это важно - DIY Photography](https://www.diyphotography.net/8-bit-vs-16-bit-color-depth-use-matters/)

- [ ] **Использование векторных изображений по сравнению с растровыми/битовыми:** ![medium] Предпочтительнее использовать векторные, а не растровые изображения (когда это возможно).

    *Почему:*
    > Векторные изображения (SVG) обычно меньше, чем картинки, и SVG отлично реагируют на изменения и масштабируются. Эти изображения можно анимировать и изменять с помощью CSS.

* [ ] **Размеры изображений:** ![medium] Установите атрибуты `width` и `height` для `<img>`, если известен конечный размер отрисованного изображения.

    *Почему:*
    > Если заданы height и width, то при загрузке страницы для изображения резервируется необходимое пространство. Однако без этих атрибутов браузер не знает размера изображения и не может зарезервировать для него соответствующее пространство. В результате макет страницы будет меняться во время загрузки (пока загружаются изображения).

* [ ] **Избегайте использования изображений в формате Base64:** ![medium] В конце концов, вы можете преобразовать крошечные изображения в base64, но это не лучший вариант.

    * 📖 [Кодирование Base64 и производительность, часть 1 и 2 Гарри Робертс](https://csswizardry.com/2017/02/base64-encoding-and-performance/)
    * 📖 [Более подробный взгляд на производительность изображений Base64– The Page Not Found Blog](http://www.andygup.net/a-closer-look-at-base64-image-performance/)
    * 📖 [Когда следует кодировать изображения в base64 (и когда не следует) | David Calhoun](https://www.davidbcalhoun.com/2011/when-to-base64-encode-images-and-when-not-to/)
   * 📖 [Base64-кодирование изображений для ускорения работы страниц | Performance and seo factors](https://varvy.com/pagespeed/base64-images.html)

* [ ] **Ленивая загрузка:** ![medium] Внеэкранные изображения загружаются лениво (всегда обеспечивается откат носкрипта).

    *Почему:*
    > Это позволит увеличить время отклика текущей страницы и избежать загрузки ненужных изображений, которые могут не понадобиться пользователю.

    *Как:*
    > ⁃ Используйте [Маяк](https://developers.google.com/web/tools/lighthouse/), чтобы определить, сколько **изображений находится за пределами экрана**. <br>
    ⁃ Для ленивой загрузки изображений используйте плагин JavaScript, например, следующий. Убедитесь, что вы нацелены только на изображения за пределами экрана. <br>
    ⁃ Также убедитесь, что альтернативные изображения, отображаемые при наведении курсора мыши или других действиях пользователя, загружаются в ленивом режиме.

    * 🛠 [verlok/lazyload: GitHub](https://github.com/verlok/lazyload)
    * 🛠 [aFarkas/lazysizes: GitHub](https://github.com/aFarkas/lazysizes/)
    * 🛠 [mfranzke/loading-attribute-polyfill: GitHub](https://github.com/mfranzke/loading-attribute-polyfill/)
    * 📖 [Ленивая загрузка изображений и видео  |  Web Fundamentals  |  Google Developers](https://developers.google.com/web/fundamentals/performance/lazy-loading-guidance/images-and-video/)
    * 📖 [5 блестящих способов ленивой загрузки изображений для ускорения загрузки страниц - Dynamic Drive Blog](http://blog.dynamicdrive.com/5-brilliant-ways-to-lazy-load-images-for-faster-page-loads/)

* [ ] **Отзывчивые изображения:** ![medium] Убедитесь, что изображения близки к размеру вашего дисплея.

    *Почему:*
    > Маленьким устройствам не нужны изображения, превышающие их область просмотра. Рекомендуется иметь несколько версий одного изображения для разных размеров.

    *Как:*
    > ⁃ Создайте изображения разных размеров для устройств, на которые вы хотите ориентироваться. <br>
    ⁃ Используйте `srcset` и `picture` для доставки нескольких вариантов каждого изображения.

     * 📖 [Отзывчивое изображениеs - Learn web development | MDN](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)

**[⬆ back to top](#изображения)**

## JavaScript

![javascript]

- [ ] **JS Минификация:** ![high] Все файлы JavaScript минифицированы, комментарии, белые пробелы и новые строки удалены из рабочих файлов *(по-прежнему актуально при использовании HTTP/2)*.

    *Почему:*
    > Удаление всех ненужных пробелов, комментариев и разрывов уменьшит размер ваших JavaScript-файлов, ускорит загрузку страниц сайта и, очевидно, облегчит загрузку для пользователя..

    *Как:*
    > ⁃ Используйте предложенные ниже инструменты для автоматического минимизации файлов до или во время сборки или развертывания..

    * 🛠 [uglify-js - npm](https://www.npmjs.com/package/uglify-js)
    * 🛠 [Online JavaScript Compressor](http://refresh-sf.com)
    * 📖 [Краткое содержание: Чем отличается HTTP/2? Нужно ли по-прежнему минифицировать и конкатенировать?](https://scaleyourcode.com/blog/article/28)

* [ ] **Без JavaScript внутри:** ![medium] *(Только для веб-сайта)* Избегайте множества JavaScript-кодов, встроенных в середину тела. Разместите код JavaScript во внешних файлах или в конце страницы (перед `</body>`) в `<head>` или в конце страницы..

    *Почему:*
    > Размещение встроенного кода JavaScript непосредственно в `<body>` может замедлить работу страницы, поскольку он загружается, пока строится DOM. Лучший вариант - использовать внешние файлы с `async` или `defer`, чтобы избежать блокировки DOM. Другой вариант - разместить некоторые скрипты внутри `<head>`. Чаще всего аналитический код или небольшой скрипт, который должен загрузиться до того, как DOM перейдет к основной обработке.

    *Как:*
    > Убедитесь, что все ваши файлы загружены с помощью `async` или `defer`, и решите с умом, какой код вам нужно внедрить в `<head>`..

     * 📖 [11 советов по оптимизации JavaScript и повышению скорости загрузки сайта](https://www.upwork.com/hiring/development/11-tips-to-optimize-javascript-and-improve-website-loading-speeds/)

* [ ] **Неблокирующий JavaScript:** ![high] Файлы JavaScript загружаются асинхронно с помощью `async` или отложенно с помощью атрибута `defer`..

    ```html
    <!-- Defer Атрибут -->
    <script defer src="foo.js"></script>

    <!-- Async Атрибут -->
    <script async src="foo.js"></script>
    ```

    *Почему:*
    > JavaScript блокирует обычный разбор HTML-документа, поэтому, когда парсер достигает тега `<script>` (в частности, внутри `<head>`), он останавливается, чтобы получить и запустить его. Добавление `async` или `defer` очень рекомендуется, если ваши скрипты расположены в верхней части страницы, но менее ценно, если непосредственно перед тегом `</body>`. Но во избежание проблем с производительностью рекомендуется всегда использовать эти атрибуты..

    *Как:*
    > ⁃ Добавьте `async` (если скрипт не зависит от других скриптов) или `defer` (если скрипт зависит от асинхронного скрипта) в качестве атрибута к тегу script. <br>
    ⁃ Если у вас небольшие скрипты, возможно, используйте место inline-скрипта над async-скриптами.

    * 📖 [Удаление блокирующего рендеринг JavaScript](https://developers.google.com/speed/docs/insights/BlockingJS)
    * 📖 [Отложите загрузку JavaScript](https://varvy.com/pagespeed/defer-loading-javascript.html)

* [ ] **Оптимизированные и обновленные JS-библиотеки:** ![medium] Все библиотеки JavaScript, используемые в вашем проекте, необходимы (предпочитайте Vanilla JavaScript для простых функций), обновлены до последней версии и не перегружают ваш JavaScript ненужными методами.

    *Почему:*
    > Чаще всего в новых версиях плагинов присутствуют оптимизации и исправления безопасности. Вы должны использовать наиболее оптимизированный код, чтобы ускорить свой проект и гарантировать, что ваш сайт или приложение не будет тормозить без устаревшего плагина.

    *Как:*
    > Если в вашем проекте используются пакеты NPM, [npm-check](https://www.npmjs.com/package/npm-check) это довольно интересная библиотека для обновления библиотек.
    > [Greenkeeper](https://greenkeeper.io/) может автоматически искать ваши зависимости и предлагать обновление каждый раз, когда выходит новая версия.

    * 📖 [Возможно, вам не нужен jQuery](http://youmightnotneedjquery.com/)
    * 📖 [Ванильный JavaScript для создания мощных веб-приложений](https://plainjs.com/)

- [ ] **Проверьте лимит размера зависимостей:** ![low] Убедитесь, что вы разумно используете внешние библиотеки, в большинстве случаев для той же функциональности можно использовать более легкую библиотеку.

    *Почему:*
    > У вас может возникнуть соблазн использовать один из 745 000 пакетов, которые вы можете найти на [npm](https://www.npmjs.com/), но вам нужно выбрать лучший пакет для ваших нужд. Например, MomentJS - потрясающая библиотека, но с большим количеством методов, которые вы, возможно, никогда не будете использовать, поэтому был создан Day.js. Он занимает всего 2 кБ против 16,4 кБ gz у Moment.

    *Как:*
    > Всегда сравнивайте и выбирайте лучшую и более легкую библиотеку для ваших нужд. Вы также можете использовать такие инструменты, как [npm trends](http://www.npmtrends.com/) для сравнения количества загрузок пакетов NPM или [Bundlephobia](https://bundlephobia.com/), чтобы узнать размер ваших зависимостей.

    * 🛠 [ai/size-limit: Предотвращение раздувания библиотек JS. Если вы случайно добавите массивную зависимость, Size Limit выдаст ошибку.](https://github.com/ai/size-limit)
    * 🛠 [webpack-bundle-analyzer - npm](https://www.npmjs.com/package/webpack-bundle-analyzer)
    * 🛠 [js-dependency-viewer - npm](https://www.npmjs.com/package/js-dependency-viewer)
    * 📖 [Size Limit: Сделайте веб светлее - Марсианские хроники, командный блог злых марсиан](https://evilmartians.com/chronicles/size-limit-make-the-web-lighter)

- [ ] **Профилирование JavaScript:** ![medium] Проверьте, нет ли проблем с производительностью в ваших файлах JavaScript (и CSS тоже).

    *Почему:*
    > Сложность JavaScript может снижать производительность во время выполнения. Выявление этих возможных проблем необходимо для обеспечения максимально комфортной работы пользователей.

    *Как:*
    > Используйте инструмент Timeline в Chrome Developer Tool, чтобы оценить события сценариев и найти те, которые могут занять слишком много времени.

    * 📖 [Ускорение выполнения JavaScript | Инструменты для веб-разработчиков  |  Google Developers](https://developers.google.com/web/tools/chrome-devtools/rendering-tools/js-execution)
    * 📖 [Профилирование JavaScript с помощью инструментов разработчика Chrome — Smashing Magazine](https://www.smashingmagazine.com/2012/06/javascript-profiling-chrome-developer-tools/)
    * 📖 [Как записывать снимки кучи  |  Tools for Web Developers  |  Google Developers](https://developers.google.com/web/tools/chrome-devtools/memory-problems/heap-snapshots)
    * 📖 [Глава 22 - Профилирование фронтенда - Blackfire](https://blackfire.io/docs/book/22-frontend-profiling)
    * 📖 [30 советов по улучшению производительности Javascript](http://www.monitis.com/blog/30-tips-to-improve-javascript-performance/)

- [ ] **Использование Service Workers:** ![medium] Вы используете Service Workers в своем PWA для кэширования данных или выполнения тяжелых задач без ущерба для пользовательского опыта вашего приложения.
   
    * 📖 [Сервисные работники: введение  |  Web Fundamentals  |  Google Developers](https://developers.google.com/web/fundamentals/primers/service-workers/)
    * 📖 [Измерение влияния работников сферы обслуживания на производительность в реальном мире |  Web  |  Google Developers](https://developers.google.com/web/showcase/2016/service-worker-perf)
    * 📖 [Что такое работники сферы обслуживания и как они помогают повысить производительность](https://www.keycdn.com/blog/service-workers/)
    * 📹 [Как работает работник сферы обслуживания? - YouTube](https://www.youtube.com/watch?v=__xAtWgfzvc)

**[⬆ back to top](#javascript)**

## Сервер

![server-side]

- [ ] **Ваш сайт использует HTTPS:**. ![high]

    *Почему:*
    > HTTPS нужен не только для сайтов электронной коммерции, но и для всех сайтов, которые обмениваются данными. Данными, которыми обменивается пользователь, или данными, передаваемыми внешним организациям. Современные браузеры ограничивают функциональность сайтов, которые не защищены. Например, геолокация, push-уведомления и рабочие службы не работают, если ваш инстанс не использует HTTPS. И сегодня гораздо проще настроить проект с SSL-сертификатом, чем раньше (и бесплатно, благодаря [Let's Encrypt](https://letsencrypt.org/)).

 * 📖 [Зачем использовать HTTPS? | Cloudflare](https://www.cloudflare.com/learning/security/why-use-https/)
 * 📖 [Включение HTTPS без ущерба для производительности сайта - Moz](https://moz.com/blog/enabling-https-without-sacrificing-web-performance)
 * 📖 [Как HTTPS влияет на производительность сайта](https://wp-rocket.me/blog/https-affects-website-performance/)
 * 📖 [HTTP против HTTPS против HTTP2 - Реальная история | Tune The Web](https://www.tunetheweb.com/blog/http-versus-https-versus-http2/)
 * 📖 [HTTP vs HTTPS — Проверьте их сами](https://www.httpvshttps.com/)

- [ ] **Вес страницы < 1500 КБ (в идеале < 500 КБ):** ![high] Уменьшите размер страницы + ресурсов настолько, насколько это возможно..

    *Почему:*
    > В идеале вы должны стремиться к размеру < 500 КБ, но состояние интернета показывает, что медиана килобайтов составляет около 1500 КБ (даже на мобильных устройствах). В зависимости от целевых пользователей, сетевого подключения, устройств, важно максимально сократить общее количество килобайт, чтобы обеспечить наилучший пользовательский опыт.

    *Как:*
    > ⁃ Все правила, содержащиеся в Front-End Performance Checklist, помогут вам максимально сократить количество ресурсов и кода.

    * 📖 [Вес страницы](https://httparchive.org/reports/page-weight#bytesTotal)
    * 🛠 [Сколько стоит мой сайт?](https://whatdoesmysitecost.com/)
    * 🛠 [web - Измерение размера полной страницы в Chrome DevTools - Stack Overflow](https://stackoverflow.com/questions/38239980/measure-full-page-size-in-chrome-devtools)

- [ ] **Время загрузки страницы < 3 секунд:** ![high] Максимально сократите время загрузки страницы, чтобы быстро донести содержимое до пользователей.

    *Почему:*
    > Быстрее работает ваш сайт или приложение, меньше вероятность отказов, другими словами, у вас меньше шансов потерять пользователя или будущего клиента. Достаточно много исследований на эту тему подтверждают этот факт.

    *Как:*
    > Используйте такие онлайн-инструменты, как [Page Speed Insight](https://developers.google.com/speed/pagespeed/insights/) или [WebPageTest](https://www.webpagetest.org/), чтобы проанализировать, что может замедлять работу сайта, и воспользуйтесь контрольным списком производительности фронтальной части сайта, чтобы улучшить время загрузки.

    * 🛠 [Сравните скорость работы вашего мобильного сайта](https://www.thinkwithgoogle.com/feature/mobile/)
    * 🛠 [Проверьте скорость и производительность вашего мобильного сайта - Think With Google](https://testmysite.thinkwithgoogle.com/intl/en-us)
    * 📖 [Среднее время загрузки страниц в 2018 году - как обстоят дела у вас? - MachMetrics Speed Blog](https://www.machmetrics.com/speed-blog/average-page-load-times-websites-2018/)

- [ ] **Time To First Byte < 1,3 секунды:** ![high] Сократите, насколько это возможно, время ожидания браузера перед получением данных.

    * 📖 [Что такое ожидание (TTFB) в DevTools и что с ним делать](https://scaleyourcode.com/blog/article/27)
    * 📖 [Мониторинг серверов с помощью бесплатных инструментов - это просто](https://scaleyourcode.com/blog/article/7)
    * 📖 [Время до первого байта (TTFB)](https://varvy.com/pagespeed/ttfb.html)
    * 🛠 [Инструмент для тестирования глобальной латентности](https://latency.apex.sh)

* [ ] **Размер куки:** ![medium] Если вы используете куки, убедитесь, что размер каждого куки не превышает 4096 байт, а в вашем доменном имени не более 20 куки.

    *Почему:*
    > Cookies обмениваются в HTTP-заголовках между веб-серверами и браузерами. Важно, чтобы размер файлов cookie был как можно меньше, чтобы минимизировать влияние на время отклика пользователя.

    *Как:*
    > Исключите ненужные файлы cookie.

    * 📖 [Cookie specification: RFC 6265](https://tools.ietf.org/html/rfc6265)
    * 📖 [Cookies](https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies)
    * 🛠 [Ограничения на использование файлов cookie в браузере](http://browsercookielimits.squawky.net/)
    * 📖 [Website Performance: Cookies Don't Taste So Good - Monitis Blog](http://www.monitis.com/blog/website-performance-cookies-dont-taste-so-good/)
    * 📖 [Лучшие практики Google в области веб-производительности #3: минимизируйте перегрузку запросов - GlobalDots Blog](https://www.globaldots.com/googles-web-performance-best-practices-3-minimize-request-overhead/)

- [ ] **Минимизация HTTP-запросов:** ![high] Всегда убеждайтесь, что каждый запрашиваемый файл необходим для вашего сайта или приложения.
 * 📖 [Комбинируйте внешние CSS](https://varvy.com/pagespeed/combine-external-css.html)
 * 📖 [Объедините внешний JavaScript](https://varvy.com/pagespeed/combine-external-javascript.html)

- [ ] **Используйте CDN для доставки ваших ресурсов:** ![medium] Используйте CDN для более быстрой доставки вашего контента по всему миру.

 * 📖 [10 советов по оптимизации производительности CDN - CDN Planet](https://www.cdnplanet.com/blog/10-tips-optimize-cdn-performance/)
 * 📖 [HTTP Кэширование  |  Web Fundamentals  |  Google Developers](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/http-caching)

- [ ] **Предоставляйте файлы по одному и тому же протоколу:** ![high] Избегайте того, чтобы ваш сайт обслуживал файлы, поступающие из источника, использующего HTTP, на вашем сайте, который, например, использует HTTPS. Если ваш сайт использует HTTPS, внешние файлы должны быть из того же протокола.

- [ ] **Сохраняйте достижимые файлы:** ![high] Избегайте запросов недоступных файлов (404).
 * 📖 [Как избежать плохих запросов](https://varvy.com/pagespeed/avoid-bad-requests.html)

- [ ] **Установите правильные заголовки HTTP-кэша:** ![high] Установите HTTP-заголовки, чтобы избежать дорогостоящих обходов между вашим браузером и сервером.
 * 📖 [Использование cache-control для кэширования в браузере](https://varvy.com/pagespeed/cache-control.html)

- [ ] **Сжатие GZIP / Brotli включено:** ![high] Используйте метод сжатия, такой как Gzip или Brotli, чтобы уменьшить размер ваших JavaScript-файлов. При меньшем размере файла пользователи смогут быстрее загрузить актив, что приведет к повышению производительности.

 * 🛠 [Проверьте сжатие GZIP](https://checkgzipcompression.com/)
 * 🛠 [Проверьте сжатие Brotli](https://tools.keycdn.com/brotli-test)
 * 📖 [Подробнее о сжатии Brotli](https://www.brotli.pro/)
 * 📖 [Can I use... Brotli](https://caniuse.com/#feat=brotli)

**[⬆ back to top](#сервер)**

---
## Перформансы и JS-фреймворки

### Angular
 * 📖 [Контрольный список производительности Angular](https://github.com/mgechev/angular-performance-checklist)

### React

 * 📖 [Оптимизация производительности - React](https://reactjs.org/docs/optimizing-performance.html)
 * 📖 [Работа с изображениями в React | Cloudinary](https://cloudinary.com/documentation/react_image_manipulation)
 * 📖 [Отладка производительности React с помощью React 16 и Chrome Devtools.](https://building.calibreapp.com/debugging-react-performance-with-react-16-and-chrome-devtools-c90698a522ad)
 * 📖 [Build Performant - React](https://web.dev/react/)

### Vue
 * 📖 [Vue - Полезные ссылки|Руководство по стилю и производительность ](https://learn-vuejs.github.io/vue-patterns/useful-links/)

## Performances and CMS

### WordPress

* 🛠 [Test Your Website Speed | WordPress Hosting by @WPEngine](https://wpengine.com/speed-tool/)

#### Статьи

 * 📖 [19 советов по ускорению работы WordPress (обновлено)](https://www.wpbeginner.com/wordpress-performance-speed/)
 * 📖 [Ускорение WordPress - как сохранить изображения, оптимизированные для Web](https://www.wpbeginner.com/beginners-guide/speed-wordpress-save-images-optimized-web/)

#### Рекомендуемые плагины

* 🛠 [Плагин кэширования для WordPress - ускорьте свой сайт с помощью WP Rocket](https://wp-rocket.me/)
* 🛠 [WP-Sweep | WordPress.org](https://wordpress.org/plugins/wp-sweep/)
* 🛠 [Imagify Image Optimizer | WordPress.org](https://wordpress.org/plugins/imagify/)

---

## Переводы

Контрольный список производительности Front-End хочет быть доступен и на других языках! Не стесняйтесь внести свой вклад!

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

## Вклад

**Открыть проблему или запрос на вытягивание, чтобы предложить изменения или дополнения.**.

## Поддержка

Если у вас есть вопросы или предложения, не стесняйтесь использовать Discord или Twitter:

* [Chat on Discord](https://discord.gg/btHQRkm)
* [Facebook](https://www.facebook.com/frontendchecklist/)
* [Twitter](https://twitter.com/thedaviddias)

## Автор

**Build with ❤️ by [David Dias](https://github.com/thedaviddias)

## Вкладчики

Этот проект существует благодаря всем людям, которые вносят свой вклад. [[Вклад]](.github/CONTRIBUTING.md).
<a href="https://github.com/thedaviddias/Front-End-Performance-Checklist/graphs/contributors">
    <img src="https://opencollective.com/front-end-checklist/contributors.svg?width=890" />
</a>


## Бэкеры

Спасибо всем нашим сторонникам! 🙏 [[Become a backer](https://opencollective.com/front-end-checklist#backer)]

<a href="https://opencollective.com/front-end-checklist#backers" target="_blank"><img src="https://opencollective.com/front-end-checklist/backers.svg?width=890"></a>


## Спонсоры

Поддержите этот проект, став его спонсором. Ваш логотип будет размещен здесь со ссылкой на ваш сайт. [[Become a sponsor](https://opencollective.com/front-end-checklist#sponsor)]

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

## Лицензия

[MIT](LICENSE)

Все иконки предоставлены [Icons8](https://icons8.com/)

**[⬆ back to top](#введение)**

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
