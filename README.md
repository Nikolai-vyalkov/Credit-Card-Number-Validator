# Отчёт о тестировании "Credit Card Number Validator"

## Краткое описание

24.06. - 24.06.2020 было проведено функциональное тестирование приложения "Credit Card Number Validator".

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* https://github.com/Nikolai-vyalkov/Credit-Card-Number-Validator/issues/1#issue-644952133
* номера карт платежной системы "AmericanExpress", не валидны


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты: 
* отчет о тестировании


В качестве тестовых данных использовались данные c cайт https://creditcardgenerator.in/:^
* cлучайно сгенерированный номер банковской карты, платежная система "Visa", страна РФ
* случайно сгенерированный номер банковской карты, платежная система "MasterCard", страна РФ 
* случайно сгенерированный номер банковской карты, платежная система "AmericanExpress", страна РФ

Тестирование производилось в следующем окружении:
*  Windows 10
*  версия Java 11


[https://creditcardgenerator.in/credit-card-generator/India/Visa]: https://creditcardgenerator.in/credit-card-generator/India/Visa
