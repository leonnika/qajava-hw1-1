# Отчёт о тестировании KeyValidator
## Краткое описание
19.03.2020 - 19.03.2020 было проведено:
* тестирование установки приложения OpenJDK 11 (LTS) под Window11 X64
* функциональное тестирование OpenJDK 11 (LTS)
* функциональное тестирование (позитовное, негативное) приложения KeyValidator.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:

* [ссылка на issues c багом №1 Необходимы права администратора](https://github.com/leonnika/qajava-hw1-1/issues/1)
* [ссылка на issues c багом №2 несоответствий версий ПО](https://github.com/leonnika/qajava-hw1-1/issues/2)
* [ссылка на issues с багом №3 Отсутствие шагов для корректного запуска ПО](https://github.com/leonnika/qajava-hw1-1/issues/3)
* [ссылка на issues c багом №4 Ошибочные результаты работы ПО](https://github.com/leonnika/qajava-hw1-1/issues/4)
 * [ссылка на issues c багом №5 Ошибочные валидные номера](https://github.com/leonnika/qajava-hw1-1/issues/5)
 * [ссылка на issues c багом №6 Ощибочные невали9дные номера](https://github.com/leonnika/qajava-hw1-1/issues/6)


## Описание процесса тестирования
В процессе тестирования использовались следующие артефакты:

* баг-репорты
* отчет о тестировании
* тест кейс


В качестве тестовых данных использовались данные:
1. [Инструкция по установке OpenJDK11 ](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md)
2. [Руководство использования](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)
3. Данные указанные в [руководстве использования](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md) :


№пп | значение  |результат
--- | --- | ---
*позитивное тестирование*| | 
1 |8f05e6a7-70e9-33d7-bfe7-b19eae0d8998 | ok
2 |80b427f8-92cd-3aae-ba04-3927fbe17c6 | ok
3 |b295bc63-9f03-3b4b-af80-969b39f8c262 |ok
4 |387eedc6-12e9-3b32-9881-63b6b5e85317 | ok
5 |c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180 |ok
*негативное тестирование*| | 
1 |18252235-78e0-44a5-8720-556f0c7da17a|fall
2 |e66075b6-ddad-445e-baf6-161b3289522b | fall
3 |b6d53250-f07e-4352-a293-6102ddf7f1ca |fall
4 |c2bc778a-1cb9-46c6-b435-0489649d2a42 | fall
5 |2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1 |fall

Тестирование производилось в следующем окружении:

1. Window11 X64
2. OpenJDK 11 (LTS)
