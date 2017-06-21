# Создание файловых систем

## Содержание урока

Теперь, когда вы на самом деле разбили диск, давайте создадим файловую систему!

<pre>$ sudo mkfs -t ext4 /dev/sdb2</pre>

Инструмент <b>mkfs</b> позволяет нам указать тип файловой системы, который мы хотим и где хотим. Вы только захотите создать файловую систему на новом секционированном диске или если вы переразбиваете старую. Скорее всего, ваша файловая система будет повреждена, если вы попытаетесь создать ее поверх существующей.

## Задание

Создайте файловую систему ext4 на USB-накопителе.

## Вопрос

Какая команда используется для создания файловой системы?

## Ответ

mkfs