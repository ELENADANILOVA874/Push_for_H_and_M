# Описание
Во избежание оттока клиентов из магазина "H&M" было решено использовать Push-уведомления c напоминанием об акциях, скидках и т.д.  Для этого я определила какое количество дней без покупки являются переломными.

Другими словами: после скольких дней без совершения покупки клиент не будет еще потерянн , но будет уже "остывший". И что бы совсем не потерятьь клиента в день "X" будем напоминать ему о возможности совершить выгодную покупку в магазине.

Шаги которые были предприняты для нахождения дня "X":
1. Нахождение и работа с базой данных о транзакциях магазина "H&M", взятой из открытых источников на сайте https://www.kaggle.com/. Обработка базы данных. 
2. На основе обработанной базы нахождение количества дней перерыва для каждого клиента. Анализ перерывов и выбор дня "X" .

Данный проект позволит нам оставить большее количетсво клиентов в роли покупателя, и не нарушать спокойствие и без того активных клиентов.
