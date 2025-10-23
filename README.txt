MultiConverterX (MCX), v18. Лицензия MIT
https://github.com/dictz
https://bkrs.info/taolun/thread-340497.html

Функции PHP конвертера
• Преобразует файлы словарей загруженные с https://bkrs.info/p47 в форматы: DSL, StarDict, MDict, HTML.
• Тоже самое с файлом словаря CC-CEDICT (https://www.mdbg.net)
• Преобразует DSL словари в форматы: StarDict, MDict, HTML.

Системные требования
• PHP 7.x.x
• ≈1Гб свободной оперативной памяти (при использовании многопоточности необходимый объём памяти может умножаться на количество потоков)

Использование
• Поместите файлы и каталоги мультиконвертера в чистый корневой публичный каталог локального сервера.
• В каталог da/ распакуйте 3 словарные базы, найти их можно по адресу https://bkrs.info/p47 (внизу страницы «Словарные базы за сегодня»)
• Возможна конвертация CC-CEDICT и словарей в формате DSL. Конвертеру потребуется преобразовать их в промежуточный формат (адаптировать), для этого поместите файлы в каталог adapter/ и отредактируйте EDITME.json согласно примеру.
• Дополнительные установки можно внести в начале файла index.php (или вынести в options.php)
• Запустите локальный сервер, откройте интернет-проводник и перейдите через адресную строку по адресу локального сервера.
• В открывшейся странице мультиконвертера укажите нужные пункты и, при необходимости, отредактируйте заголовки и описания (клик по строке заголовка в таблице)
• Конвертация может длиться долго, узнайте подробнее нажав кнопку « i ».


HTML конвертеры, dsx/html_tools/:
• cc-cedict_converter.html - Конвертация CC-CEDICT (https://www.mdbg.net) в форматы StarDict и MDict.
                             https://bkrs.info/taolun/thread-343071.html
• bkrs_converter.html      - Конвертация словарей загруженных с https://bkrs.info/p47 (внизу страницы «Словарные базы за сегодня») в форматы StarDict и MDict.
                             https://bkrs.info/taolun/thread-343086.html
• dsl_converter.html       - Конвертация словарей в формате DSL в форматы StarDict и MDict.
                             https://bkrs.info/taolun/thread-343200.html
• dictz.html               - DictZip сжатие файлов (GZip сжатие для произвольного чтения, соответствует стандарту RFC 1952. https://sourceforge.net/projects/dict/, http://www.dict.org)
                             https://bkrs.info/taolun/thread-124987-post-896709.html#pid896709

О форматах
• DSL:
  - http://lingvo.helpmax.net/ru/вопросы-и-затруднения/dsl-compiler/компиляция-словаря/
  - https://ru.wikipedia.org/wiki/GoldenDict
• MDict:
  - https://www.mdict.cn
  - https://zh.wikipedia.org/zh-cn/MDict
• StarDict:
  - https://ru.wikipedia.org/wiki/StarDict
  - https://ru.wikipedia.org/wiki/GoldenDict
• HTML, Dictionary Shell X (DSX, dsx.html) :
  - Открыть можно многими браузерами использующими проект «Chromium»: Samsung Internet, Google Chrome, Microsoft Edge и другими.


Использованные ресурсы
• dsx/format_doc/
• https://github.com/tabler/tabler-icons
• https://github.com/mdsills/cccedict
• https://github.com/nodeca/pako
• https://bkrs.info/
• https://www.mdbg.net/
• https://hexed.it/
• https://home.unicode.org/


Благодарность
• Использованным ресурсам
• Форуму https://bkrs.info/, его участникам и отдельно @!@бкрс@@, за ценные советы, подсказки и полезный словарь.

