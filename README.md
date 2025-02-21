# Тестирование API

Здесь содержаться работы по тестированию API для приложения ["Интернет-магазин"](https://qa.demoshopping.ru/), включая:

🔹 Проверка XML на ошибки<br>
🔹 Создание первой коллекции в Postman для тестирования методов API "Интернет-магазин", включая использование переменных окружения и настройку авторизации<br>
   Документация в [Swagger](https://qa.demoshopping.ru/api-docs/#/) для интернет-магазина Demoshopping<br>
🔹 Первые простые автотесты – добавление тестов для методов Products, Cart, Orders и Payment с проверкой статуса, тела и времени ответа<br>
🔹 Тестирование SOAP-сервисов<br>
🔹 Генерация тестовых данных и тест-кейсы – добавление генерации случайных данных для запросов и создание тестов для различных методов API<br>

# Первое задание заключалось в проверке XML на ошибки

Дано:
```xml
<?xml version="1.0" encoding="UTF-8"?>

<note date="12/05/2022">
  <to><name>Alena</name></to>
  <lastname>Petrova</lastname>
  <from>Alex</from>
  <update>12/05/2022</update>
</note>
```
Исправленный вариант:
```xml
 <?xml version="1.0" encoding="UTF-8"?>

<note date="12/05/2022">
  <to><name>Alena</name></to>
  <lastname>Petrova</lastname>
  <from>Alex</from>
  <update date="12/05/2022"></update>
</note>
```


[Первая коллекция в Рostman, тестирование API онлайн-магазина](https://www.postman.com/sartr/workspace/qademoshopping/collection/40972255-de278550-caf5-48ab-affe-9fa383882124?action=share&creator=40972255&active-environment=40972255-a3ee1a91-cdca-4e6b-ac56-d69b6ff1f65d)

[Тестирование SOAP в Postman](https://www.postman.com/sartr/workspace/soap-country-info-service/collection/40972255-9d82bc7a-b179-4889-9f80-a4743c84b7a9?action=share&creator=40972255)

[Тест-кейсы](https://github.com/padvoiskaya/API/commit/dbc5396ebdea9835f5da304368180b4156799d9d#diff-885b3a96a8c2b344356536af397c2d315ec3f803951fa01b974bb55521fa7665)
