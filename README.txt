MultiConverterX (MCX), версия 17. Лицензия: MIT
-------------------------------------------------------------
Функции мультиконвертера:
• Преобразует файлы словарей загруженные с https://bkrs.info/p47 в форматы: DSL, StarDict, MDict, HTML.
• Тоже самое с файлом словаря CC-CEDICT (https://www.mdbg.net)
• Преобразует DSL словари в форматы: StarDict, MDict, HTML.

Системные требования:
• PHP 7.x.x
• От 1Гб свободной оперативной памяти.

Использование:
• Поместите файлы и каталоги мультиконвертера в чистый корневой публичный каталог локального сервера.
• В каталог da/ распакуйте 3 словарные базы, найти их можно по адресу https://bkrs.info/p47 (внизу страницы «Словарные базы за сегодня»)
• Возможна конвертация CC-CEDICT и словарей в формате DSL. Конвертеру потребуется преобразовать их в промежуточный формат (адаптировать), для этого поместите файлы в каталог adapter/ и отредактируйте EDITME.json согласно примеру.
• При необходимости, некоторые настройки можно выполнить в начале файла index.php.
• Запустите локальный сервер, откройте интернет-проводник и перейдите через адресную строку по адресу локального сервера.
• В открывшейся странице мультиконвертера укажите нужные пункты и, при необходимости, отредактируйте заголовки и описания (клик по строке заголовка в таблице)
• Нажмите «Конвертировать». Конвертация может длиться долго, узнайте подробнее нажав кнопку « i ».

-------------------------------------------------------------
dsx/html_tools/:
• cc-cedict_converter.html - Конвертация CC-CEDICT в форматы StarDict и MDict.
• bkrs_converter.html      - Конвертация словарей загруженных с https://bkrs.info/p47 в форматы StarDict и MDict.
• dictz.html               - DictZip сжатие файлов словарей.
• font_inspect.html        - Просмотр глифов и их кодов в файлах ttf.

Ссылки связанные с проектом:
• https://bkrs.info/taolun/thread-340497.html
• https://github.com/dictz
• Примеры результатов конвертации: https://max.ru/join/cEt06A6ZIKKnCtLIgNVZS4-KdWr8n5B8zeUJrqLDSJs

О форматах и чем открыть:
• DSL:
  • http://lingvo.helpmax.net/ru/вопросы-и-затруднения/dsl-compiler/компиляция-словаря/
  • https://ru.wikipedia.org/wiki/GoldenDict
• MDict:
  • https://www.mdict.cn
  • https://zh.wikipedia.org/zh-cn/MDict
• StarDict:
  • https://ru.wikipedia.org/wiki/StarDict
  • https://ru.wikipedia.org/wiki/GoldenDict
• HTML, Dictionary Shell X (DSX, dsx.html) :
  • Открыть можно многими браузерами использующими проект «Chromium»: Samsung Internet, Google Chrome, Microsoft Edge и другими.

Использованные ресурсы:
• dsx/format_doc/
• https://bkrs.info/
• https://hexed.it/
• https://www.mdbg.net/
• https://home.unicode.org/
• https://github.com/tabler/tabler-icons
• https://github.com/mdsills/cccedict
• https://github.com/nodeca/pako
• https://github.com/hlorenzi/font-js

Благодарность:
• Использованным ресурсам
• Форуму https://bkrs.info/, его участникам и отдельно @!@бкрс@@, за ценные советы, подсказки и полезный словарь.
-------------------------------------------------------------
