# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

28.12.2020 - 28.12.2020 было проведено функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 2 часа

В результате тестирования выявлены следующие дефекты:
* [Отсутствует возможность валидации карт с номером длиной 19 цифр](https://github.com/Budenovsky/homework-Credit-Card-Number-Validator/issues/1#issue-775434748)
* [Отсутствует возможность валидации платежных карт American Express](https://github.com/Budenovsky/homework-Credit-Card-Number-Validator/issues/2#issue-775439102)
* [Отсутствует возможность валидации платежных карт Diners Club - Carte Blanche и Diners Club - International](https://github.com/Budenovsky/homework-Credit-Card-Number-Validator/issues/3#issue-775442801)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* тест-кейс

*Примечание\*: не указывайте артефакты "для галочки". Если вы сюда напишите **тест-план**, то мы попросим вас его показать (а если не покажете - то отправим работу на доработку). Пишите только то, что реально существует и требуется в задании.*

В качестве тестовых данных использовались данные https://www.freeformatter.com/credit-card-number-generator-validator.html:
* VISA:
  * 4532664991886484: Result is OK
  * 4916189189871771: Result is OK
  * 4532339974781925462: Result is OK
* MasterCard:
  * 5496237022267338: Result is OK
  * 2720995039693797: Result is OK
  * 2221002013840546: Result is OK
* American Express (AMEX):
  * 379676851686048: Result is OK
  * 372924525451408: Result is OK
  * 341252829002265: Result is OK
* Discover:
  * 6011598940344002: Result is OK
  * 6011136387312974: Result is OK
  * 6011963717537405768: Result is OK
* JCB:
  * 3541430561295162: Result is OK
  * 3528527741177678: Result is OK
  * 3534271683926600735: Result is OK
* Diners Club - North America:
  * 5409939081933934: Result is OK
  * 5546029455635192: Result is OK
  * 5401249231242733: Result is OK
* Diners Club - Carte Blanche:
  * 30361650281967: Result is OK
  * 30370712839894: Result is OK
  * 30320083578654: Result is OK
* Diners Club - International:
  * 36930240111431: Result is OK
  * 36325723893086: Result is OK
  * 36523015467086: Result is OK
* Maestro:
  * 5018361773995399: Result is OK
  * 5038959469875282: Result is OK
  * 6763337860138395: Result is OK
* Visa Electron:
  * 4508145694023435: Result is OK
  * 4026994907341974: Result is OK
  * 4175000425966810: Result is OK
* InstaPayment:
  * 6387978981306647: Result is OK
  * 6394348349209951: Result is OK
  * 6385339257714067: Result is OK


Тестирование производилось в следующем окружении:
* 64-разрядная операционная система Windows 10 Домашняя
* Java 11.0.9.1
* IntelliJ IDEA 2020.3 (Community Edition)
