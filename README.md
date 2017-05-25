# temp

[8.2](#Processes2). 
Первоначально создан в 2004 году Джоном Грубером (англ. John Gruber) и Аароном Шварцем. Многие идеи языка были позаимствованы из существующих соглашений по разметке текста в электронных письмах. Реализации языка Markdown преобразуют текст в формате Markdown в валидный, правильно построенный XHTML и заменяют левые угловые скобки («<») и амперсанды («&») на соответствующие коды сущностей. Первой реализацией Markdown стала написанная Грубером реализация на Perl, однако спустя некоторое время появилось множество реализаций от сторонних разработчиков (см. ниже). Реализация на Perl распространяется по лицензии типа BSD. Реализации Markdown на различных языках программирования включены (или доступны в качестве плагина) во многие системы управления содержимым.

Примеры синтаксиса[править | править вики-текст]
Ниже приведены примеры использования Markdown, однако это далеко не полное руководство. Полное описание языка может быть найдено на официальном сайте[5]. Символы, которые обычно рассматриваются в Markdown как специальные, могут быть экранированы с помощью обратного слеша. Например, последовательность «\*» выведет символ «*», а не будет являться признаком начала выделенного текста. Кроме того, Markdown не преобразует текст внутри «сырых» блоков XHTML. Таким образом, в Markdown-документ можно включать секции XHTML, заключив их предварительно в теги уровня блока.

Текст с выделением или логическим ударением:
 *выделение* (например, курсив)
 **сильное выделение** (например, полужирное начертание)
Программный код:
 `какой_то_программный_код($аргумент)`
    `какой_то_программный_код_с_отступом_от_начала_строки_4_знака`
Зачёркнутый текст:
    необходимо сделать ~~одну~~ другую вещь
Списки:
 * элемент маркированного списка
 - ещё один элемент ненумерованного списка
 + буллеты элементов могут быть разными
 1. Элемент нумерованного списка
 2. Элемент №2 того же списка
 9. Элемент №3 списка — элементы нумеруются по порядку, цифра в начале строки не имеет значения
Заголовки:
Создание заголовков производится путём помещения знака решетки перед текстом заголовка. Количество знаков «#» соответствует уровню заголовка. HTML предоставляет 6 уровней заголовков.

# Заголовок первого уровня
#### Заголовок четвёртого уровня
Первые два уровня заголовка также имеют альтернативный синтаксис:

Заголовок первого уровня
========================
Заголовок второго уровня
------------------------
Цитаты (тег blockquote):
>Данный текст будет заключен в HTML-теги <blockquote></blockquote>
> Данный текст будет заключен в HTML-теги <blockquote></blockquote>
Ссылки:
[Текст ссылки](адрес://ссылки.здесь "Заголовок ссылки")
или

[Текст ссылки][тег]
и где-нибудь в документе (например в самом низу)

[тег]: адрес://ссылки.здесь "Заголовок ссылки"
Изображения:
Реализации Markdown[править | править вики-текст]
C#[6]
C[7][8][9][10]
ColdFusion[11]
Common Lisp[12]
Go[13]
Haskell[14]
Java[15][16]
JavaScript[17]
Lua[18]
newLISP[19]
Perl[20]
PHP[21]
Python[22][23]
Ruby[24][25]
Scala[26]
Tcl[27]
Расширения[править | править вики-текст]
Приведённые ниже приложения реализуют Markdown, расширяя его синтаксис дополнительной функциональностью:

MultiMarkdown (C)[28]
Text::MultiMarkdown (Perl) модуль, реализующий расширение MultiMarkdown[29]
PHP Markdown Extra[30]
python-markdown2 (Поддерживает некоторые расширения PHP Markdown)[23]
python-markdown (Имеет систему расширений для добавления нового синтаксиса)[22]
Markout (Java)[31]
Pegdown (Java)[16]
Maruku (Ruby)[25]
Pandoc (Haskell)[14][32]
Руководства[править | править вики-текст]
Markdown: Dingus онлайн-конвертер[33]
Markdown cheat sheet[34]
Конвертеры[править | править вики-текст]
из HTML в Markdown
html2text.py (написано на Python)[35]
Markdownify (на PHP)[36]
Make.text — букмарклет, преобразующий любую веб-страницу в Markdown[37]
XHTML-to-Markdown XSLT (XSLT-таблица стилей, работает только с XHTML)[38]
Pandoc — написанная на Haskell библиотека по преобразованию различных форматов, поддерживает несколько диалектов Markdown (markdown — диалект от pandoc, markdown_strict — оригинальный Markdown без расширений, markdown_phpextra — диалект от PHP, markdown_github — диалект от github) может преобразовывать из и в Markdown, HTML, reStructuredText, LaTeX, и другие.[14]
Другие форматы в Markdown
odt2txt (написанный на Python скрипт для преобразования файлов из формата OpenDocument в Markdown)[39]
word_markdown_macro (макрос Microsoft Word, преобразующий некоторую часть форматирования Word в Markdown)[40]
Веб-приложения, использующие Markdown[править | править вики-текст]
Вики:
DokuWiki (с помощью плагина)
ikiwiki
Oddmuse
PmWiki (с помощью плагина)
Блоги:
Tumblr — изначально отключён, но можно использовать, включив в настройках.
scriptogr.am
CMS:
Drupal — content-фильтр Markdown[41]
Magento — с помощью модуля[42]
Plone — «родная» поддержка в Plone 3
TYPO3 — с помощью плагина af_markdown[43]
RadiantCMS — один из видов разметки, доступный «из коробки»[44]
Веб-фреймворки:
Ruby on Rails — требуется установка BlueCloth, Maruku[45]
Yii — виджет CMarkdown, входит в стандартную поставку фреймворка
Webasyst — входит в стандартную поставку PHP-фреймфорка в виде плагина к бесплатному приложению «Блог»
Поддержка текстовыми редакторами[править | править вики-текст]
Универсальные редакторы: TextMate, BBEdit (с версии 8.6), Vim (с помощью специального пользовательского режима[46], написанного Беном Вильямсом), Emacs(с помощью специального пользовательского режима[47], написанного Джейсоном Блевинсом), TextWrangler, Smultron, Sublime Text, Geany, Atom.
Редакторы для блогов: Ecto[48], MarsEdit
Плагины для редактора среды Eclipse от ThinkTank Mathematics[49]
Плагины для текстового редактора gedit[50]
Текстовый редактор iA Writer в версии для Mac OS[51]
Текстовый редактор ReText для GNU/Linux[52]
WYSIWYM-редактор Texts для Windows/Mac OS[53]
## 8.2 <a name="Processes2"></a>Проверка 
[[PDF]](Bib.md)
<A name="Biblio.md#PDF"> PDF </A>
[[PDF]](#Bib.md)
[[PDF]](Bib.md#PDF)
[[PDF]](#Bib.md#PDF)
