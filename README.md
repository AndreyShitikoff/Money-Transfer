# Отчёт о тестировании "Money Transfer"

**Краткое описание**

13.09.2020 было проведено модульное тестирование функции Money Transfer.

На тестирование затрачено: 1 час.

В программе IDEA был написан код для проверки трансзакций со следующими переменными 

int balance = 2_000_000_000;

int transfer = 500_000_000;

int total = balance + transfer;

**Ожидаемый результат:**

int total = 2_500_000_000

**Фактический результат:**

int total = -1794967296

[Issue](https://github.com/AndreyShitikoff/Money-Transfer/issues/1)

**Описание процесса тестирования**

В процессе тестирования использовались следующие программы.

* OpenJDK 11

В качестве тестовых данных использовались данные из  [Задачи №1 - Money Transfer](https://github.com/netology-code/javaqa-homeworks/tree/master/programming)


Тестирование производилось в следующем окружении:

* Windows 10 PRO
* OpenJDK 11