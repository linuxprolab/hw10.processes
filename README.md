# Домашнее задание 10 

Работаем с процессами

Описание/Пошаговая инструкция выполнения домашнего задания:
Задания на выбор:

1. Написать свою реализацию ps ax используя анализ /proc. Результат ДЗ - рабочий скрипт который можно запустить
2. Написать свою реализацию lsof. Результат ДЗ - рабочий скрипт который можно запустить
3. Дописать обработчики сигналов в прилагаемом скрипте, оттестировать, приложить сам скрипт, инструкции по использованию. Результат ДЗ - рабочий скрипт который можно запустить + инструкция по использованию и лог консоли
4. Реализовать 2 конкурирующих процесса по IO. пробовать запустить с разными ionice. Результат ДЗ - скрипт запускающий 2 процесса с разными ionice, замеряющий время выполнения и лог консоли
5. Реализовать 2 конкурирующих процесса по CPU. пробовать запустить с разными nice. Результат ДЗ - скрипт запускающий 2 процесса с разными nice и замеряющий время выполнения и лог консоли

Выполнено:
1. Скрипт `ps.sh`, выводящий PID, USER, STATE, CMD атрибуты запущенных процессов 



