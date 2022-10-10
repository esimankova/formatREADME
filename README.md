#
# Инструкция для работы с Git

## Работа с локальными репозиториями

* git init - создает новый репозиторий .git 

* git add FolderName - добавление файла FolderName в индекс

* git commit -m "Message" - запись изменений в репозиторий

* git log - открывает журнал изменений

* git diff - покажет отличие текущего состояния файла от сохраненного

## Ветки 

* git branch - покажет ветки проекта

* git branch BranchName - создаст новую ветку

* git checkout  BranchName - перейдет на указанную ветку

* git merge BranchName - сольет указанную ветку с той, в которой мы находимся

## Работа с удаленными репозиториями

* git clone link - загрузка репозитория с (GitHub)

* git push - направляет в интернет локальные изменения

* git pull - загрузит в git с GitHub

* git remote add origin - удаленное добавление источника

* git branch -M main - укажет основную ветку

* git push -u origin main - направит в интернет все, что мы делаем

#
# Инструкция для работы с Markdown

## Выделение текста

Чтобы выделить тескт курсивом, необходимо обрамить его звездочками (*) или знаком нижнего подчекривания (_). Например, *вот так* или _так_.

Чтобы выделить текст полужирным, необходимо обрамить его двойными звездочками (**) или двойным знаком нижнего подчеркивания(__). Например, **вот так** или __так__.

Альтернативные способы выделения текста жирным или курсивм нужны для того, чтобы мы могли совмещать оба эти способа. Например _тескт может быть выделен курсивом и при этом быть **полужирным**_.

Чтобы выделить текст, необходимо обрамить его (). Например, вот так.

## Списки

Чтобы добавить ненумерованные списки, необходимо пункты выделить звездочкой (*) или знаком (+). Например, вот так:
* Элемент 1
* Элемент 2
* Элемент 3
+ Элемент 4
+ Элемент 5

Чтобы добавить нумерованные списки, необходимо пункты пронумеровать. Например, вот так:
1. Первый пункт
2. Второй пункт

## Ссылки

Ссылка создается подобно изображению, но без (!): [Нажми на меня](https://youtu.be/dQw4w9WgXcQ)

## Работа с таблицами

Для того, чтобы создать таблицу, необходимо заключить ее элементы в такие символы как: (|) и (-). Например, вот так:
| Заголовок 1 | Заголовок 2 | Заголовок 3 |
| ----------- | ----------- | ----------- |
| Текст 1.1 | Текст 2.1 | Текст 3.1 |
| Текст 1.2 | Текст 2.2 | Текст 3.2 |
| Текст 1.3 | Текст 2.3 | Текст 3.3 |

При этом, длина ячеек может отличаться в редакторе, но в конечном виде таблица будет поделена в соответствии со столбцами.

## Цитаты

Для обозначения цитат в языке Markdown используется знак «больше» (>). Например, вот так:
> Цитата 1
>> Цитата 2
>>> Цитата 3
>
> Цитата 4

## Заключение 

Markdown – это облегченный язык разметки, который является инструментом преобразования кода в HTML. Главной особенностью данного языка является максимально простой синтаксис, который служит для упрощения написания и чтения кода разметки, что, в свою очередь, позволяет легко его корректировать. 