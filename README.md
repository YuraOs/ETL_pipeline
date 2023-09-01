# ETL_pipeline
## Описание:
Написан скрипт для сборки отчета по основным метрикам: DAU, Просмотры, Лайки, CTR. С помощью Airflow автоматизирована ежедневная отправка отчетов в телеграм бот.
Разработана система поиска аномалий на основе статистического метода межквартильный размах. Построен доверительный интервал, выход за границы которого говорит об аномальности наблюдения. Границы интервала вычислены с помощью квартилей.
## Стек:
 **Apache Airflow**, **Pandas** (matplotlib, seaborn, telegram, airflow).
