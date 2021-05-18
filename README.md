# **Задача 3 - Postman Echo**

В этой задаче мы сэмулируем ситуацию, в которой SUT уже запущен, а мы из теста просто обращаемся к нему.

Что нужно сделать:

1.    Создайте новый проект на базе Gradle
2.    Добавьте необходимые зависимости (если вы не пишите схему, то только rest-assured)
3.    Напишите тест, взяв сам запрос из кода выше
4.    Изучите ответ и напишите JsonPath-выражение вместо строк /* --> ваша проверка здесь <--*/, которое проверит, что в нужном поле хранятся отправленные вами данные.