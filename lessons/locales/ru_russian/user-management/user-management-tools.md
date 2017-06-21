# Инструменты управления пользователями

## Содержание урока

Большинство корпоративных сред используют системы управления для управления пользователями, учетными записями и паролями. Тем не менее, на одном компьютере компьютере есть полезные команды для запуска управления пользователями.

<b>Добавление пользователей</b>

Вы можете использовать AddUser или useradd команду. Команда AddUser содержит больше полезных функций, таких как создание домашнего каталога и многое другое. Есть файлы конфигурации для добавления новых пользователей, которые могут быть настроены в зависимости от того, что вы хотите передать пользователю по умолчанию.

<pre>$ sudo useradd bob</pre>

Вы увидите, что приведенная выше команда создает запись /etc/passwd пароль для боба, устанавливает группы по умолчанию и добавляет запись в  файл /etc/shadow.

<b>Удаление пользователей</b>

Чтобы удалить пользователя, вы можете использовать команду userdel.

<pre>$ sudo userdel bob</pre>

Это в основном делает все возможное, чтобы отменить изменения файлов через useradd.

<b>Изменение паролей</b>

<pre>$ passwd bob</pre>

Это позволит вам изменить пароль себя или другого пользователя (если вы рут).

## Задание

Создайте нового пользователя затем измените свой пароль и логин в качестве нового пользователя.

## Вопрос

Какая команда используется для изменения пароля?

## Ответ

passwd

