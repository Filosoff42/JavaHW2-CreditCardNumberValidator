# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

13.01.2021 было проведено функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 1 час.

В результате тестирования выявлены следующие дефекты:
* [Валидные номера карт длиной менее 16 символов не проходят валидацию в Credit Card Number Validator](https://github.com/Filosoff42/JavaHW2-CreditCardNumberValidator/issues/1#issue-784684833)
* [Валидные номера карт длиной более 16 символов не проходят валидацию в Credit Card Number Validator](https://github.com/Filosoff42/JavaHW2-CreditCardNumberValidator/issues/2#issue-784685780)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [Условия Задачи 2 по тестированию Credit Card Number Validator](https://github.com/netology-code/javaqa-homeworks/tree/master/intro#%D0%B7%D0%B0%D0%B4%D0%B0%D1%87%D0%B0-2---credit-card-number-validator)

В качестве тестовых данных использовались случайно сгенерированные валидные номера карт по ссылке https://www.freeformatter.com/credit-card-number-generator-validator.html:
* American Express: 347433884920385
* VISA: 4485842143995112298

Тестирование производилось в следующем окружении:
* ОС: 
    * Microsoft Windows 10
    * 64-разрядная
    * сборка 19041.685
* Java:
    * openjdk version "11.0.9.1" 2020-11-04
    * OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.9.1+1)
    * OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.9.1+1, mixed mode)
* IntelliJ Idea версии 2020.3.1 (Community Edition)