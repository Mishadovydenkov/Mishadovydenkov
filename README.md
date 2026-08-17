![Header][def]

[def]: https://github.com/Mishadovydenkov/Mishadovydenkov/blob/main/assets/header.gif

<div id="header" align="center">

`         Связаться со мной         `



[![Telegram](https://img.shields.io/badge/telegram-white?style=for-the-badge&logo=telegram&logoColor=%2326A5E4)](https://t.me/hangenu)
[![Telegram](https://img.shields.io/badge/Email-white?style=for-the-badge&logo=maildotru&logoColor=%23FFCD00
)](mailto:dovydenkov98@mail.ru)
</div>

## 👋 Привет, меня зовут Михаил!
Я - QA Engineer с опытом ручного тестирования внутренних web-систем с интеграциями и сложной бизнес-логикой.

Специализируюсь на функциональном, регрессионном и интеграционном тестировании, проверке API и обмена данными с 1С, работе с тестовой документацией, SQL-проверках и анализе дефектов.

Работал с Jira, TestIT, Confluence, PostgreSQL, Postman, Swagger, запускал автотесты перед релизом.

## Инструменты :
![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=Jira&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=Swagger&logoColor=white)
![SQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)
![Bash](https://img.shields.io/badge/GNU%20Bash-4EAA25?style=for-the-badge&logo=GNU%20Bash&logoColor=white)

## Проекты

### Проект 1: MetaCheck — Telegram-бот для учёта рабочего времени сотрудников

**Роль:** QA Engineer (разработка + полное тестирование)

**Цель проекта**
Разработать Telegram-бота для фиксации рабочего времени сотрудников и самостоятельно покрыть его полной тестовой документацией. Бот должен корректно обрабатывать основные, негативные и граничные сценарии.

**Что реализовано:**
- Чекин / чекаут сотрудников
- Проверка геолокации (радиус офиса)
- Учёт опозданий, раннего ухода и переработок
- Управление рабочим графиком (роль администратора)
- Валидация действий пользователя
- Хранение данных в SQLite

**Что сделано в части тестирования:**
- Разработал тест-кейсы на позитивные, негативные и граничные сценарии (включая Boundary Value Analysis)
- Составил Test Plan, Requirements Traceability Matrix и чек-листы (Smoke, Pre-release)
- Провёл полный регрессионный прогон (**30/30 Passed**)
- Подготовил Test Summary Report

**Стек:** Python · aiogram · SQLite · Telegram Bot API

**Тестовая документация:**

| Документ | Ссылка |
|---------|--------|
| Test Plan | [MetaCheck_Test_Plan.xlsx](https://github.com/Mishadovydenkov/telegram-employee-checkin/blob/main/docs/qa/MetaCheck_Test_Plan.xlsx) |
| Test Cases | [MetaCheck_Test_Cases.xlsx](https://github.com/Mishadovydenkov/telegram-employee-checkin/blob/main/docs/qa/MetaCheck_Test_Cases.xlsx) |
| Test Summary Report | [MetaCheck_Test_Summary_Report.docx](https://github.com/Mishadovydenkov/telegram-employee-checkin/blob/main/docs/qa/MetaCheck_Test_Summary_Report.docx) |