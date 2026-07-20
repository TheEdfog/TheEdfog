# Алим Нармаматов

Data Engineer. Основные направления моей работы — ETL/ELT-пайплайны, распределённая обработка, аналитические модели данных и контроль качества.

В коммерческих проектах я работал с мастер-данными, lakehouse-пайплайнами, Feature Store, большими наборами логов и нагрузочным тестированием ML API. В инженерных решениях ценю прозрачные преобразования, автоматические проверки и документацию, которая соответствует коду.

## Основные проекты

- [Оптимизация join в PySpark](https://github.com/TheEdfog/pyspark-join-workshop) — материалы проведённого мной университетского мастер-класса: MovieLens 25M, анализ физических планов и восемь вариантов домашних заданий.
- [Платформа аналитики продаж](https://github.com/TheEdfog/sales-data-platform) — пайплайн на PostgreSQL/Greenplum, Airflow и ClickHouse с витриной и исполняемыми проверками качества данных.
- [Нагрузочное тестирование API](https://github.com/TheEdfog/api-load-tester) — асинхронный CLI-инструмент с контролем RPS и concurrency, расчётом p50/p95/p99 и JSON-отчётами.
- [Streaming Lakehouse](https://github.com/TheEdfog/retail-streaming-lakehouse) — локальный стенд Kafka и Spark Structured Streaming с event-time дедупликацией, quarantine и конфигурацией Iceberg/Trino.
- [Контракты событий](https://github.com/TheEdfog/event-contract-guard) — runtime-валидация событий, проверка совместимости схем, quarantine, метрики Prometheus и Helm chart.

## Стек

Python, SQL, PySpark, Spark, Airflow, Databricks, Delta Lake, Greenplum, ClickHouse, PostgreSQL, Oracle, Trino, Docker, Git и CI/CD.

## Примеры задач из коммерческого опыта

- Разработал переиспользуемый Data Quality-фреймворк с более чем 70 проверками схемы, пропусков, дубликатов, кардинальности, связей и бизнес-правил.
- Работал над централизованным слоем мастер-данных объёмом более 1,5 млн записей для 80+ IT- и 200+ бизнес-пользователей.
- С помощью Spark исследовал около 55 млн логов транзакций и локализовал этапы потери данных в ML-пайплайне.
- Разрабатывал инструменты нагрузочного тестирования ML API: более 5 000 запросов в секунду; результаты помогли снизить потребление CPU и памяти примерно на 70% без нарушения SLA.

Сейчас углубляю знания Kubernetes, контрактов данных и production observability.
