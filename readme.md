# Инструкция для работы с Git и удалёнными репозиториями

![.Git Logo](git-logo.png)

|  |  |
|--|--|
| Тип | Распределённая система управления версиями |
| Разработчик | Software Freedom Conservancy |
| Язык разработки | Си, Perl, Tcl, Python и C++ |
| Операционная система | кроссплатформенность |
| Язык интерфейса | Английский |
| Первый выпуск | 7 апреля 2005 |
| Последняя версия | 2\.37.0 от 27 июня 2022 |
| Сайт разработчика | Git ([git-scm.com](http://git-scm.com)[)](https://git-scm.com/) |
| Страница загрузки | Git - Загрузка ([git-scm.com](http://git-scm.com)[)](https://git-scm.com/downloads) |

> ## **Free and Open Source**
>
> Git is released under the [GNU General Public License version 2.0](https://opensource.org/licenses/GPL-2.0), which is an [open source license](https://opensource.org/docs/osd). The Git project chose to use GPLv2 to guarantee your freedom to share and change free software---to make sure the software is free for all its users.

## Что такое Git?

Git - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.

## Подготовка репозитория

Для создание репозитория необходимо выполнить команду *git init* в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)

## Создание коммитов

### Git add

Для добавления измений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла>*

### Просмотр состояния репозитория

Для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли измения в файлах, или их не было.

### Создание коммитов

Для того, чтобы создать коммит(сохранение) необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m "<сообщение к коммиту>*. Все файлы для коммита должны быть ***ДОБАВЛЕНЫ*** и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.

## Перемещение между сохранениями

Для того, чтобы перемещаться между коммитами, используется команда *git checkout*. Используется она в папке с пепозиторием следующим образом: *git checkout <номер коммита>*

## Журнал изменений

Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда *git log*. Для этого достаточно выполнить команду *git log* в папке с репозиторием

## Ветки в Git

### Создание ветки

Для того, чтобы создать ветку, используется команда *git branch*. Делается это следующим образом в папке с репозиторием: *git branch <название новой ветки>*

## Слияние веток

Для того чтобы дабавить ветку в текущую ветку используется команда *git merge <name branch>*

## Удаление веток

Для удаления ветки ввести команду "git branch -d 'name branch'"

---

### Дополнительные материалы для изучения

* Git - Documentation [git-scm.com](https://git-scm.com/doc)
* Git для новичков (часть 1) / Хабр [habr.com](https://habr.com/ru/post/541258/)
* Git для новичков (часть 2) / Хабр [habr.com](https://habr.com/ru/post/542616/)
* 30 команд Git, необходимых для освоения интерфейса командной строки Git / Хабр [habr.com](https://habr.com/ru/company/ruvds/blog/599929/)

![шпаргалка](git_cheat_sheet.png)

---

Изменения в ветке sem02.04 для создания конфликта между ветками:
- sem02.01
- sem02.04