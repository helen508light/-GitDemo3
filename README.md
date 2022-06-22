# **"GIT"** - система контроля версий

**Система контроля версий** — это
система, записывающая изменения в файл или набор файлов в течение времени и
позволяющая вернуться позже к определённой версии.
## Основные команды:
1. **"Git config"** - позволяет просматривать и настраивать
параметры, контролирующие все аспекты работы Git, а также его внешний вид.
2. **"Git init"** - инициализируете репозиторий, создаёт ветку с именем
master (по умолчанию).
3. **"Git add"** - добавляет содержимое рабочего каталога в индекс (staging area) для последующего коммита.
4. **"Git status"** - показывает состояния файлов в рабочем каталоге и индексе: какие файлы изменены, но не добавлены в индекс; какие ожидают коммита в индексе.
5. **"Git commit"** - берёт все данные, добавленные в индекс с помощью git add, и сохраняет их слепок во внутренней базе данных, а затем сдвигает указатель текущей ветки на этот слепок.
6. **"Git diff"** - используется для вычисления разницы между любыми двумя Git деревьями.
7. **"Git difftool"** - запускает внешнюю утилиту сравнения для показа различий в двух деревьях, на случай если вы хотите использовать что-либо отличное от встроенного просмотрщика git diff.
8. **"Git reset"** - используется в основном для отмены изменений. Также эта команда может изменить файлы в рабочем каталоге при использовании параметра --hard.
9. **"Git rm"** - используется в Git для удаления файлов из индекса и рабочей копии.
10. **"Git mv"** - удобный способ перемещать файл.
11. **"Git clean"** - используется для удаления мусора из рабочего каталога.
12. **Git log** - показывает сделанные ранее комиты.
13. **Git checkout** - позволяет переключаться между ветками.
14. **Git branch** - команда для работы с ветками.
15. **Git merge** - сливает ветки.
16. **Git log --graph** - показывает коммиты в виде "дерева"
17. **Git clone** - копирует внешний репозиторий на локальный.
18. **Git clone** - позволяет скачать все из текущего репозитория и автоматически сделать merge с нашей версией.
19. **Git push** - отправляет локальную версию репозитория во внешниюю (требуется авторизация).
20. **Git remote add "name address"** - добавляет ссылку на внешний репозиторий

---

# Инструкция для работы с Marcdown

## **Выделение текста**
Чтобы выделить текст курсивом, необходимо обрамить его звездочками ( * ) или знаком нижнего подчеркивания ( _ ): *Пример*, _Пример_

Чтобы выделить текст полужирным, необходимо обрамить его двойными звездочками (**) или двойным знаком нижнего подчеркивания ( __ ):  **Пример**, __Пример__

Альтернативные способы выделения текста жирным или курсивом нужны для того, чтобы мы могли совмещать оба этих способа: _**Пример**_

## **Список**
Чтобы добавить ненумерованные списки, необходимо пункты выделить звездочкой (*) или знаком (+). Пример:
* Элемент 1
* Элемент 2
+ Элемент 3
+ Элемент 4

Чтобы добавить нумерованные списки, необходимо пункты обозначать порядковым номером с точкой:
1. Первый пункт
2. Второй пункт

## **Работа с изображением**
Чтобы вставить изображение в текст, достаточно написать следующее: ![Скрин из VS](Images.jpg)

## **Ссылки**
Markdown поддерживает два стиля оформления ссылок: 
* Гиперссылка, с немедленным указанием адреса (внутритекстовая).
* Гиперссылка, подобная сноске.

Подразумевается, что помимо URL-адреса существует еще текст ссылки. Он заключается в квадратные скобки. Для создания внутритекстовой гиперссылки необходимо использовать круглые скобки сразу после закрывающей квадратной. Внутри них необходимо поместить URL-адрес. В них же возможно расположить название, заключенное в кавычки, которое будет отображаться при наведении, но этот пункт не является обязательным.

![Пример 1](https://gist.github.com/Jekins/2bf2d0638163f1294637#Links "Обучающий материал из открытых источников")

Пример [2]

[2]:[https://gist.github.com/Jekins/2bf2d0638163f1294637#Links]

## **Цитаты**
Для обозначения цитат в языке Markdown используется знак «больше» («>»). Его можно вставлять как перед каждой строкой цитаты, так и только перед первой строкой параграфа. Также синтаксис Markdown позволяет создавать вложенные цитаты (цитаты внутри цитат). Для их разметки используются дополнительные уровни знаков цитирования («>»). Цитаты в Markdown могут содержать всевозможные элементы разметки. Цитаты в языке Markdown выглядят следующим образом:

>"Что разум человека может постигнуть и во что он может поверить, того он способен достичь"
>>"Сложнее всего начать действовать, все остальное зависит только от упорства."

## **Работа с таблицами**
Для создания таблицы необходимо вертикальными "|"  и горизонтальными чертами "-" обозначить колонки. 

Пример:

Первый | Второй | Третий
---|---|---
*Один* | 123456 | 000000
*Два* | 123456 | 000000
*Три* | 123456 | 000000

---

# Работа с удаленными репозиториями.

Для работы с удаленными репозиториями, необходиимо создать аккаунт на сервисе: https://github.com/

## Использование внешнего репозитория.

Чтобы начать работу с внешним репозиторием, необходимо:
1. Получить ссылку на репозвнешний репозиторий.
2. Открыть новую папку и запустить терминал.
3. В терминале указываем команду git clone (вставляем ссылку на внешний репозиторий).

Чтобы загрузить локальный репозиторий на GitHub, необходимо:
1. На сервисе GitHub создать удаленный репозиторий и скопировать ссылку.
2. В терминале указать команду git remote add origin (ссылка на удаленный репозиторий).
3. Указать основную ветку: git branch -M (наименование ветки).
4. Загружаем локальный репозиторий на внешний по команде git push -u origin main.
5. Пройти авторизацию (при первичной загрузке).

Чтобы внести изменения из локального репозитория в удаленный, необходимо воспользоваться командой git push

Добавляю вторую ветку