# О книге

Книга разделена на шесть глав:

* [Глава I. Основы Python](book/Part_I.md)
* [Глава II. Повторное использование кода](book/Part_II.md)
* [Глава III. Регулярные выражения](book/Part_III.md)
* [Глава IV. Запись и передача данных](book/Part_IV.md)
* [Глава V. Работа с сетевым оборудованием](book/Part_V.md)
* [Глава VI. Ansible](book/Part_VI.md)


Первая глава книги посвящена основам Python. В ней рассматриваются:

* начало работы с Python, выбор редактора и ОС, виртуальные окружения
* использование Git и GitHub
* типы данных Python
* как создавать базовые скрипты
* контроль хода программы
* работа с файлами

Кроме того, в 8 разделе показаны примеры использования пройденых тем для решения задач.

Разделы 1-3 посвящены подготовке к работе с Python: установке пакетов, выбору редактора и ОС.
Кроме того, в них рассматриваются система установки пакетов Python и способ изоляции разных версий Python и пакетов Python друг от друга.

В разделах 4-7 объясняются основы Python.
Вы узнаете, какие базовые типы данных поддерживает Python, как с ними работать, какие возможности и ограничения есть у них.
В [5 разделе](book/05_basic_scripts/README.md) рассматривается создание базовых скриптов, а также как запрашивать информацию у пользователя и как передавать аргументы созданному скрипту.

> Если вы знаете основы Python, то пролистайте их хотя бы в [презентации](https://github.com/natenka/pyneng-slides)

[Шестой раздел](book/06_control_structures/README.md) посвящен контролю хода программы: условиям (if/else), циклам (for, while) и работе с исключениями.
А в [седьмом разделе](book/07_files/README.md) мы завершаем знакомство с основами Python описанием принципов работы с файлами.

Девятый и одинадцатый разделы посвящены повторному использованию кода: функциям и модулям.
В [девятом разделе](book/09_functions/README.md) описано, как создавать функцию, какие типы параметров и аргументов поддерживает функция.
[Десятый раздел](book/10_useful_functions/README.md) посвящен полезным встроенным функциям и тому как их использовать.

В [одинадцатом разделе](book/11_modules/README.md) рассматриваются модули, как их создавать и как повторно использовать код из другого скрипта.
[Двенадцатый раздел](book/12_useful_modules/README.md) посвящен различным модулям Python, таким как: subprocess, ipaddress, argparse и другим.

[Третяя глава](book/Part_III.md) полностью посвящена регулярным выражениям.
Тут рассматривается и синтаксис регулярных выражений, и как с ними работать в Python.
После этой главы вы с легкостью сможете получать нужную информацию из вывода команд.

[В 16 разделе](book/16_unicode/README.md) рассматривается стандарт Unicode и его использование в Python.

В [17 разделе](book/17_serialization/README.md) рассматриваются форматы CSV, YAML и JSON.
Формат CSV позволит работать с табличными данными.
Это могут быть данные из какой-то таблицы, базы данных или системы мониторинга.

YAML удобно использовать для записи параметров в структурированном формате - как вручную, так и автоматизированно.
Кроме того, YAML используется как язык описания сценариев в Ansible.

JSON подойдет для сохранения полученной информации.
Кроме того, он часто используется как формат передачи данных в разных API.

В [18 разделе](book/18_db/README.md) рассматривается работа с базами данных на примере SQLite.
Тут рассматриваются и основы SQL, и как работать с базами данных из Python.

[Девятнадцатый раздел](book/19_ssh_telnet/README.md) посвящен подключению к сетевому оборудованию с помощью Telnet и SSH.
Тут рассматриваются несколько модулей, так как каждый из них использует немного отличающийся подход.

В [20 разделе](book/20_concurrent_connections/README.md) рассматривается, как подключаться к оборудованию параллельно, используя потоки и процессы.

В [21 разделе](book/21_jinja2/README.md) рассматривается язык шаблонов Jinja2.
Jinja2 позволит создавать шаблоны конфигураций с нуля.
Таким образом, вместо замены параметров в текстовом файле вы легко сможете генерировать нужные команды с помощью Python.

[22 раздел](book/14_textfsm/README.md) посвящен TextFSM.
Это библиотека от Google, которая позволяет обрабатывать вывод команд show (и любых других аналогичных).
Для обработки команды создается отдельный шаблон, который описан с помощью регулярных выражений.

[Шестая глава](book/Part_VI.md) рассматриваются основы работы с Ansible, а также модули для работы с Cisco.
Этой информации будет достаточно, чтобы начать использовать Ansible, но, так как это не все его возможности, остальное вынесено в отдельную книгу.

И, наконец, в [последнем разделе](book/25_additional_info/README.md) собраны те темы, которые не вошли в другие разделы, но которые все равно очень полезны.

В [конце книги](resources.md) собраны рекомендации по дальнейшему обучению.

### Книга всегда будет бесплатной

Книга всегда будет оставаться бесплатной.
Поэтому вам не нужно переживать, что она будет удалена.

### ОС, Python

Все примеры и выводы в книге показываются на Debian Linux.

В книге используется Python 3.6.
Для большинства примеров подойдет и Python 3.4, 3.5.
И только в некоторых требуется версия 3.6 или 3.5+.
Это всегда явно указано и, как правило, касается дополнительных возможностей.

> Версия книги для Python 2.7 находится по [ссылке](https://natenka.gitbooks.io/pyneng/content/v/python2.7/).

[Варианты виртуальной машины для курса](book/01_intro/README.md).

### Примеры

> Все примеры, которые используются в книге, можно скачать в [репозитории](https://github.com/natenka/pyneng-examples-exercises/).


Примеры, которые рассматриваются в разделах книги, являются обучающими.
Это значит, что они не обязательно показывают лучший вариант решения задачи, так как они основаны только на той информации, которая рассматривалась до этого.

Кроме того, довольно часто примеры, которые давались в разделах, развиваются в заданиях.
То есть, вам нужно будет сделать более хорошую, универсальную, правильную версию кода.

Если есть возможность, лучше набирать код, который используется в книге, самостоятельно.
Или, как минимум, скачать примеры и попробовать что-то в них изменить.
Так информация будет лучше запоминаться.

Если такой возможности нет, например, когда вы читаете книгу в дороге,
можно попробовать повторить примеры самостоятельно позже.

Но, в любом случае, обязательно нужно делать задания.

### Задания

> Все задания и вспомогательные файлы можно скачать в [репозитории](https://github.com/natenka/pyneng-examples-exercises/).


Если в заданиях раздела есть задания с буквами (например, 5.2a), то можно выполнить сначала задания без букв, а затем с буквами.
Задания с буквами, как правило, немного сложнее заданий без букв и развивают/усложняют идею в соответствующем задании без буквы.

Однако, если получается, лучше делать задания по порядку.

В книге специально не выложены ответы на задания.
К сожалению, когда есть ответы, очень часто вместо того, чтобы попытаться решить сложное задание самостоятельно, подглядывают в ответы.

Конечно, иногда возникает ситуация, когда никак не получается решить задание.
Тогда попробуйте отложить его и сделать какое-то другое.

> На [stackoverflow](http://stackoverflow.com/) есть ответы практически на любые вопросы. Так что, если google отправил вас туда, это с большой вероятностью значит, что ответ найден. Запросы, конечно же, лучше писать на английском. По Python очень много материалов и, как правило, подсказку найти легко.

Ответы могли бы показать, как ещё можно выполнить задание или как более правильно/короче выполнить его.
Но на этот счет тоже не переживайте, так как, скорее всего, в следующих разделах встретится пример, в котором будет показано, как писать такой код.

### Тесты


Для части тем книги созданы тесты:

* [Типы данных. Часть 1](https://goo.gl/forms/xKHX5xNM8Pv5sQDf2)
* [Типы данных. Часть 2](https://goo.gl/forms/igxR3ub3tQg3ycX53)
* [Контроль хода программы. Часть 1](https://goo.gl/forms/2TmGcrhG11h2SdLn1)
* [Контроль хода программы. Часть 2](https://goo.gl/forms/KZGaDquGlUmOz2kG3)
* [Функции и модули. Часть 1](https://goo.gl/forms/M1DpbdD0brVbdp1G3)
* [Функции и модули. Часть 2](https://goo.gl/forms/rNvdX9bHw8wLajJp2)
* [Регулярные выражения. Часть 1](https://goo.gl/forms/5UpkJbm1dORqs4bP2)
* [Регулярные выражения. Часть 2](https://goo.gl/forms/ltuOAO62yLlZkEmm1)
* [Базы данных](https://goo.gl/forms/wtGgmWg0vow1Cyqo1)


Эти тесты можно использовать:
* для проверки знаний
* как задания

Очень полезно пройти тест после прочтения соответствующей темы.
Он позволит вспомнить материал темы, а также попробовать на практике разные аспекты работы с Python.

Постарайтесь сначала ответить самостоятельно, а затем подсмотреть ответы в ipython по тем вопросам, в которых вы сомневаетесь.

### Презентации

Для всех тем книги есть презентации.
По ним удобно быстро просматривать информацию и повторять.

> Скачать все презентации можно в [репозитории](https://github.com/natenka/pyneng-slides/tree/py3-pdf)


## Обновление книги

01.09.2017 книга была переведена на Python 3.6.

Но она еще может дополняться, а также будут исправляться ошибки и опечатки.
Поэтому если вы не будете читать книгу в ближайшее время, то лучше сохраните ссылку на онлайн версию книги, а не PDF/mobi/epub.
А когда решите читать, скачаете, если нужно, свежую версию.

Подробнее об обновлениях можно почитать в [changelog](CHANGELOG.md).

Gitbook отображает, когда были сделаны последние изменения, поэтому легко можно определить, были ли изменения за последнее время.

![gitbook_update](https://raw.githubusercontent.com/natenka/PyNEng/master/images/gitbook_update.png)


## Форматы книги

Книгу можно читать в нескольких форматах:
* [онлайн](https://natenka.gitbooks.io/pyneng/content/)
* [PDF/ePub/Mobi](https://www.gitbook.com/book/natenka/pyneng/details)

Они автоматически обновляются, поэтому всегда содержат одинаковую информацию.

> Пожалуйста, не выкладывайте скачанные версии книги. Вместо этого просто давайте ссылку на книгу.

## Комментарии

Для обсуждения книги, заданий и других вопросов, связанных с Python и автоматизацией в целом, создана [команда PyNEng в Slack](https://pyneng-slack.herokuapp.com/).

> Обсуждения на GitBook закрыты.

