# -GitDemo3

# **Файл по контролю версий домашнее задания для семинара №1**

## *Синтаксис языка markdawn.*

## **Выделение текста**
Для написания заголовков надо использовать "#" данный заголовок второго уровня.

Для написания *курсива* используем * текст. *
Для того что бы выделить текст **полужирным** шрифтом используем 
** текст. **

Для написания зачеркнутого текста нужно использовать "~~" 
~~текст~~

Для написания курсивного начертания нужно использовать два нижних подчеркивания _текст_

## **Списки**

Что бы сделать не номерной список нужно написать в начале строки *
*  Текст 1
*  Текст 2
*  Текст 3

Что бы сделать номерной список нужноиспользовать в начале строки цифру с точкой и пробел.

1. Текст 1
2. Текст 2
3. Текст 3

## **Цитаты**

Что бы обозначить цытату в языке Markdawn нужно использовать знак ">"
> Текст 

>     Первый уровень цитаты;
>>    Второй уровень цитаты;
>>>   Третий уровень цитаты;
>>>>  Четвертый уровеьн цитаты.

## **Основные команды Git:**

* git init - инициализация локального репозитора;
* git status - получения информации от git о его текущем состоянии;
* git add - добавить файл или файлы к следуйщему commit;
* git commit -m"messange" - создание commit;
* git log - вывод на экран истории всех commit с их хеш-кодами;
* git checkout - переход от одного commit к другому;
* git checkout master - вернуться к актуальному состоянию;
* git diff - увидеть разницу между текущим файлом и конечным.

## **Работа с удаленным репозиторием**

* git clone <URL-адрес репозитория> - Копитование внешнего репозитория на локальный; 
* git pull  - Получение изменений и слияния с локальной версией;
* git push - Отправка локального репозитория во внешний
* git remote add <name> <adress> - Добавляет ссылку на удаленный репозиторий;
* git remote -v - Проверка добавленных ссылок;
* git remote set-url origin - Смена адресса отправления;
* git fetch origin - Загружает ветки из удаленного репозитория.