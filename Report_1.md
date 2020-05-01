#Отчёт о тестировании OpenJDK11 for Windows 10 pro

## Краткое описание

Дата проведения тестирования: _27/04/2020 - 27/04/2020 гг._

Проведено инсталляционное, тестирование совместимости приложения OpenJDK 11.0.7.10 (x64) с Java version 11.0.7. 
Так же проведено функциональное тестирование приложения KeyValidator.class 
 
На тестирование затрачено: 0.5 часа.

В результате тестирования выявлены следующие дефекты:

<issu с github>
<issu с github>

В процессе тестирования использовались следующие артефакты:

* [Форма](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/report.md) отчетности
* Тест-кейс

Предварительные условия:

Установить [приложение](https://docs.google.com/document/d/1CzzJeI0DCYAg7UKJivOpLj5eIfEO5tE094zAtgUL9CE/edit?usp=sharing) OpenJDK 

Скачать файл-[приложение](https://drive.google.com/open?id=1s5bjDBZAQsnPpF95f1ZFDR3Tyo8RncDA) KeyValidator.class

Шаги:
1. Открыть терминал при помощи команды CMD
2. В открывшемся окне ввести команду *java -version*
3. Проверить, что версия java 8+
4. Закрыть терминал.
5. Установить приложение OpenJDK согласно [инструкции](https://docs.google.com/document/d/1CzzJeI0DCYAg7UKJivOpLj5eIfEO5tE094zAtgUL9CE/edit?usp=sharing)  
6. Скачать KeyValidator.class
7. Запустить терминал при помощи команды CMD
8. В терминале перейти в папку с файлом KeyValidator.class
9. В строке ввода указать java KeyValidator, передать предоставленные ключи. 

   Ключей для валидации можно передавать произвольное количество (мин. 1)
10. Нажать Enter

**Ожидаемый результат:**

Приложение OpenJDK запускается, конфликта с Java version 11.0.7 нет.

Валидные ключи выдают сообщение Ok, невалидные Fail.(см. пример ниже)

 * Result for 00000000-0000-0000-0000-000000000000: OK
 * Result for 00000000-0000-0000-0000-000000000001: FAIL

**Фактический результат:**

приложение OpenJDK запускается, конфликта с Java version 11.0.7 нет.

Ключии не соответствуют заявленным в проверочных.


В качестве тестовых данных использовались данные: 

**Ключи для проверки**

Валидные ключи:

* 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998
* 80b427f8-92cd-3aae-ba04-3927fbe17c6
* b295bc63-9f03-3b4b-af80-969b39f8c262
* 387eedc6-12e9-3b32-9881-63b6b5e85317
* c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180

Невалидные ключи:

* 18252235-78e0-44a5-8720-556f0c7da17a
* e66075b6-ddad-445e-baf6-161b3289522b
* b6d53250-f07e-4352-a293-6102ddf7f1ca
* c2bc778a-1cb9-46c6-b435-0489649d2a42
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1



####Тестирование производилось в следующем окружении:

OS - Win 10 PRO ver. 1709, build 16299.1087
***
Java version 11.0.7
***
OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.7+10)
***
OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.7+10, mixed mode)

