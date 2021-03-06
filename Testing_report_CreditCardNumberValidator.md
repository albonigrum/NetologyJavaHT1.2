# Отчёт о тестировании CreditCardNumberValidator

## Краткое описание

04.06.2020 - 04.06.2020 было проведено функциональное тестирование приложения CreditCardNumberValidator.

На тестирование затрачено: 2 часа

В результате тестирования выявлены следующие дефекты:
* https://github.com/albonigrum/NetologyJavaHT1.2/issues/4

## Описание процесса тестирования

В качестве тестовых данных использовались данные 
[отсюда](https://www.freeformatter.com/credit-card-number-generator-validator.html) и 
[отсюда](https://www.dcode.fr/luhn-algorithm):

13-значные:
* 4916703127087
* 4716002403274
* 4716834318674

14-значные:
* 04195257180392
* 96030017896798
* 79233018331119

15-значные:
* 180019243735265
* 210067420439312
* 180070814737727

16-значные:
* 5545030241707619
* 5498060693919757
* 5152724148428329

17-значные:
* 38709283344436437
* 46971954646292496
* 60662623744562697

18-значные:
* 858871499442658812
* 248933356478950663
* 124362876984810807

19-значные:
* 8473241226219945020
* 9504348111520241470
* 5771741247894820374


Тестирование производилось в следующем окружении:
* Windows 10 64-bit
* openjdk version "11.0.7"
* Запуск производился в IntelliJ IDEA 2020.1.2 (Community Edition)
