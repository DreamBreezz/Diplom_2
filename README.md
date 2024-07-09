# Diplom_1

Втораяl часть дипломного проекта курса QA Java Automation в Яндекс.Практикум.

Цель проекта — создать API-тесты для нескольких ручек сайта
[Stellar Burgers](https://stellarburgers.nomoreparties.site/).

Документация API:
[link](https://code.s3.yandex.net/qa-automation-engineer/java/cheatsheets/paid-track/diplom/api-documentation.pdf).

## Использованные технологии
* Java 11
* Maven 3.8
* JUnit 4
* Rest Assured 5.3.0
* Allure 2.20.0
* Lombok 1.18.32
* Gson 2.8.9
* JavaFaker 1.0.2

## Настройка проекта
Не требуется.

## Запуск тестов:

Прогон тестов:
```bash 
mvn clean test
```

Открытие Allure отчёта:
```bash
mvn allure:serve
```
