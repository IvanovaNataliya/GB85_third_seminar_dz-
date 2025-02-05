# GB85_third_seminar_dz

2385 third seminar dz

# Инструкция для работы с Markdown

## Заголовки
Для того чтобы написать заголовок в Markdown, необходимо использовать знак Хеш(#). Если "необходимо несколько уровней заголовков, h1 - h6, нужно изменить количество хешей(#) перед текстом заголовка. Например вот так:
# Дети-счастье.
## Дети-счастье.
### Дети-счастье.
#### Дети-счастье.

Или Другой вариант: написать текст первого заголовка, затем нажать Enter и на следующей строке указать любое количество знаков равно (=). Например вот так:

Дети-счастье
==== 
## Выделение текста

Чтобы выделить текст курсивом необходимо обрамить его (*) или знаком нижнего подчеркивания (_) . Например, *Дети-счастье* или _Дети-счастье_.

Чтобы выделить текст полужирным, необходимо обрамить его двойными звездочками(**) или двойным знаком нижнего поддчеркивания(__). Например, **Дети-счастье** или __Дети счастье__.

Альтернативные способы выделения текста полужирным или курсивом нужны для того, чтобы мы могли совмещать оба эти способа. Например, _Текст может быть выделен курсивом и при этом быть **полужирным**_.

Чтобы написать текст с эффектом зачеркивания, нужно обрамить его  двойным знаком тильды (~~). Например вот так:

~~Дети-не счастье~~
##  Ссылки

Чтобы поставить гиперссылку без анкора, нужно взять URL в угловые скобки. С e-mail - аналогично. Например вот так:

-Это ссылка на образовательный портал <http://GeekBrains>

Чтобы вставить ссылку с анкором, то тогда текст ссылки заключаем в квадратные скобки, а адрес страницы в круглые. Например вот так:

Это образовательный портал [GeekBrains](http://GeekBrains)

## Работа с изображениями

Чтобы вставить изображение в текст, достаточно написать следующее:
![Привет, это Варвара!](%D0%92%D0%B0%D1%80%D0%B2%D0%B0%D1%80%D0%B0.PNG)
## Списки

Чтобы добавить ненумерованные списки, необходимо пункты выделить звездочкой(*) или знаком (+). Например вот так:
* Элемент 1
* Элемент 2
* Элемент 3
+ Элемент 4

Чтобы добавить нумерованные списки необходимо пункты просто пронумеровать. Например вот так:
1. Первый пункт
2. Второй пункт

## Работа с таблицами
Чтобы рисовать таблицы, нужно использовать знак (|), чтобы добавлять горизонтальные полосы и выравнивание в столбцах нужно ставить несколько знаков минус (---), обрамленных знаками двоеточие (:--:) . В зависимости от того, с какой стороны поставить знак двоеточие(:), по тому краю и призойдет выравнивание. Например вот так:

| Раз | два | три | 1 | 2 | 3 |
| :--- | :---: | ---: | :--- | ---: | ---: |
| 1 | 2 | 3 | раз | два | три |
|три|два |раз|3|2|1|
## Цитаты

Чтобы выделить цитату, нужно текст обрамить угловыми скобками(<>). Например вот так:
>Не суйся в дела, которые тебя не касаются, но будь верен своему делу, а твое дело-любовь к истине, да причем, тебе ниикто и не помешает служить ей, если ты не будешь вмешиваться не в свои дела. Итак, **учиться, учиться, и еще таки учиться**! К черту политику, да здравствует наука!

 Автор этой бессмертной фразы Виссарион Белинский

## Абзацы и параграфы
В Markdown все блочные элементы(заголовки, списки, абзацы и т.д.)- все, что визуально начинается с новой строки выделяется пустой строкой. Чтобы добавить пустую строку необходимо два раза поставить символ переноса строки (нажать на Enter)

## Горизонтальные линии
Создать горизонтальную линию можно поместив три и больше звездочек(* * *), минусов (- - -) или  нижних подчеркиваний(_ _) на отдельной строке. Например вот так:

---
***
___
## Заключение
Зачем использовать Markdown? На то есть причины:

* Если нужно быстро одготовит материал к публикации

* Если нужен блог с лаконичным дизайном

* Возможность писать красивые сообщения в WhatsApp или Telegram

* Для написания документации к проекту.

**Но во всех этих случаях нужно одно-сделать минимальную вёрстку текста так, чтобы он выглядел опрятно и чтобы его можно было читать без специальных программ**.

# Инструкция по работе с командами Markdown.

1. Чтобы инициализировать локальный репозиторий, нужно вызвать команду "**git init**" в терминале.

2. Чтобы получить информацию от git о его текущем состоянии, нужно вызвать команду "**git status**" в терминале.

3. Чтобы добавить файл или файлы к следующему коммиту, нужно в терминале вызвать команду "**git add**".

4. Чтобы создать сохранение,т.е. коммит, нужно в терминале вызвать команду "**git commit**", дальше поставить пробел, тире, m и в ковычках ("") написать, что было изменено.

5. Чтобы вывести на экран историю всех коммитов с их хеш-кодами, нужно в терминале ввести команду "**git log**"

6. Чтобы создать новую ветку нужно в терминале вызвать команду "**git branch**", пробел и название новой ветки.

7. Чтобы посмотреть список всех веток в репозитории нужно в терминале вызвать команду "**git branch**".

8. Чтобы перейти от одной ветки к другой, нужно в терминале вызвать команду "**git checkout**" нажать пробел и ввести название другой ветки.

9. Чтобы удалить ветку, нужно в терминале ввести команду "**git branch**", пробел, тире(-), букву d, пробел и ввести название ветки.

# Инструкция по работе с удаленными репозиториями на Githab.

1. Делаем форк(fork) интересующего нас аккаунта.

2. Делаем git clone для нашей версии этого репозитория.

3. Мы создаем ветку с предлагаемыми изменениями.

4. Производим все изменения только в этой ветке.

5. Отправляем эти изменения на свой аккаунт(push)

6. В окне на Githab появляется возможность отправить pull request.
