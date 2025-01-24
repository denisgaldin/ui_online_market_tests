# Проект по тестированию интернет-магазина <a target="_blank" href="https://www.online-market.by/">Online-Market</a>

![main page screenshot](pictures/online_market_main_page.png)

---

### Список проверок, реализованных в web автотестах

1. Открытие первого монитора в списке.
2. Проверка фильтра "Диагональ" значение "15.6".
3. Добавление монитора в корзину.
4. Удаление монитора из корзины.
5. Добавление монитора в список сравнения.
6. Удаление монитора из списка сравнение.
7. Очистка списка сравнения.
8. Добавление монитора в избранное.
9. Удаление монитора из избранного.
10. Очистка списка избранного.

## Используемый стек технологий и инструментов

|                             Python                             |                             Pytest                             |                             Selene                             |                             Selenoid                             |                              Git                               |                                 Jenkins                                 |                                Allure                                 |                             Allure TestOps                             |                                 PyCharm                                  |                             Telegram                             |
|:--------------------------------------------------------------:|:--------------------------------------------------------------:|:--------------------------------------------------------------:|:----------------------------------------------------------------:|:--------------------------------------------------------------:|:-----------------------------------------------------------------------:|:---------------------------------------------------------------------:|:----------------------------------------------------------------------:|:------------------------------------------------------------------------:|:----------------------------------------------------------------:|
| <img width="55" height="55" src="/pictures/icons/python.svg"/> | <img width="55" height="55" src="/pictures/icons/pytest.svg"/> | <img width="55" height="55" src="/pictures/icons/selene.png"/> | <img width="55" height="55" src="/pictures/icons/selenoid.png"/> | <img width="55" height="55" src="/pictures/icons/github.svg"/> | <img width="55" height="55" src="/pictures/icons/jenkins-original.svg"> | <img width="55" height="55" src="/pictures/icons/allure_report.png"/> | <img width="40" height="40" src="/pictures/icons/allure_testops.svg"/> | <img width="40" height="40" src="/pictures/icons/pycharm-original.svg"/> | <img width="40" height="40" src="/pictures/icons/telegram.png"/> |

## <img width="4%" title="Jenkins" src="/pictures/icons/jenkins-original.svg"> Запуск проекта в Jenkins
#### Для запуска автотестов в Jenkins
1. __Открыть проект <a href="https://jenkins.autotests.cloud/job/online_market_diplom/1/allure/">в Jenkins</a>__
2. __Выбрать пункт `Build with Parameters`__
3. __Результат запуска сборки можно посмотреть в отчете Allure__