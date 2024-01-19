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
