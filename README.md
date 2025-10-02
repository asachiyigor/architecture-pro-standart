# Architecture Pro Standard - Банк "Стандарт"

Архитектурная документация для цифровой трансформации банка "Стандарт".

## Структура проекта

### Task 1 - IT Landscape
- IT-ландшафт уровня L2
- Бизнес-возможности и поддерживающие системы

### Task 2 - Требования (FURPS+)
- Функциональные требования
- Нефункциональные требования (Performance, Reliability, Security, Supportability)
- Дополнительные требования (+)

### Task 3 - MVP: Открытие депозитов онлайн
- ADR (Architecture Decision Record)
- C4 диаграммы (Context, Container) в PlantUML
- Архитектура микросервисов (.NET Core)
- Интеграция с АБС через SOAP

### Task 4 - Передача ставок в кол-центр
- ADR с детальным roadmap
- C4 диаграммы контейнеров в PlantUML
- Rate API + Redis Cache
- SFTP для партнерских кол-центров
- Roadmap: 8 недель (4 фазы)

### Task 5 - Заявка на кредит онлайн
- ADR с интеграцией БКИ и скоринга
- C4 диаграммы в PlantUML
- Credit Application Service
- Асинхронная интеграция с кредитным конвейером (Kafka)
- Roadmap: 11 недель (4 фазы)

## Диаграммы

PlantUML диаграммы автоматически конвертируются в PNG при пуше в репозиторий.

### Просмотр диаграмм

Файлы `.puml` можно просматривать:
- На GitHub (автоматически генерируются PNG)
- В IDE с плагином PlantUML
- На [PlantUML Online Server](http://www.plantuml.com/plantuml/uml/)

## Технологический стек

- **Backend:** .NET Core, ASP.NET MVC 4.5
- **Frontend:** PHP, React.js
- **Databases:** MS SQL Server, Oracle
- **Cache:** Redis
- **Message Queue:** Kafka
- **Scheduling:** Hangfire
- **Monitoring:** Prometheus, Grafana
- **Logging:** ELK Stack

## Timeline

- **Task 3 (MVP Депозиты):** 6 недель
- **Task 4 (Передача ставок):** 8 недель
- **Task 5 (Кредиты онлайн):** 11 недель
- **Total MVP:** ~25 недель (6 месяцев)

## Автор

Архитектор цифровой трансформации
