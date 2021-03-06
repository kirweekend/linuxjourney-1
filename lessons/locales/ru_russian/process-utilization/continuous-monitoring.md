# Непрерывный мониторинг

## Содержание урока

Эти инструменты мониторинга хороши, когда у вас возникают проблемы, но что касается машин, которые имеют проблемы, когда вы не смотрите. Для этого вам нужно будет использовать инструмент непрерывного мониторинга, который будет собирать, сообщать и сохранять информацию о вашей системе. В этом уроке мы рассмотрим отличный инструмент для использования <b>sar</b>.

<b>Установка sar</b>
Sar - это инструмент, который используется для проведения исторического анализа в вашей системе, сначала убедитесь, что он установлен, установив пакет sysstat <b>sudo apt install sysstat</b>.

<b>Настройка сбора данных</b>
Обычно, как только вы устанавливаете sysstat, ваша система автоматически начнет собирать данные, если вы не сможете включить ее, измените поле ENABLED в /etc/default/sysstat.

<b>Использование sar</b>

<pre>$ sudo sar -q</pre>

Эта команда будет перечислять детали с начала дня.

<pre>$ sudo sar -r</pre>

При этом будут перечислены сведения об использовании памяти с начала дня.

<pre>$ sudo sar -P</pre>

В этом разделе перечислены сведения об использовании ЦП. 

Чтобы посмотреть представление другого дня, вы можете зайти в /var/log/sysstat/saXX, где XX - это день, который вы хотите просмотреть.

<pre>$sar -q /var/log/sysstat/sa02</pre>

## Задание

Установите sar на свою систему, начните сбор и анализ ресурсов вашей системы.

## Вопрос

Какой инструмент позволяет мониторить системные ресурсы?

## Ответ

sar
