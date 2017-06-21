# Использование диска

## Содержание урока

Есть несколько инструментов, которые вы можете использовать для использования ваших дисков: 

<pre>
pete@icebox:~$ df -h
Filesystem     1K-blocks    Used Available Use% Mounted on
/dev/sda1       6.2G  2.3G  3.6G  40% /
</pre>

Команда df показывает использование ваших смонтированных файловых систем. Флаг -h дает вам удобный для чтения формат. Вы можете видеть, что такое устройство, и сколько мощности используется и доступно.

Допустим, ваш диск заполняется, и вы хотите знать, какие файлы или каталоги занимают это пространство, для этого можете использовать команду <b>du</b>. 

<pre>$ du -h</pre>

Это покажет вам использование диска в текущем каталоге, в котором вы находитесь, вы можете заглянуть в корневой каталог с помощью <b>du -h /</b>.

Обе эти команды настолько похожи в синтаксисе, что трудно запомнить, какой из них использовать. Чтобы проверить, сколько памяти вашего <b>диска</b> <b>свободно</b> использует df. Чтобы проверить <b>использование диска</b>, введите du. 

## Задание

Посмотрите на использование вашего диска и свободное пространство как с du, так и с df.

## Вопрос

Какая команда используется, чтобы показать, сколько свободного места на вашем диске?

## Ответ

df