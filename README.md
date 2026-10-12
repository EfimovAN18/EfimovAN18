<h1 align="center">Алексей Ефимов</h1>
<p align="center"><b>Data Analyst → Data Engineer</b> · Python · SQL · статистика · A/B-тесты</p>
<p align="center">Студент Московского Политеха · Москва</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" />
  <img src="https://img.shields.io/badge/DataLens-FC3F1D?style=flat-square&logo=yandex&logoColor=white" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
</p>

---

## Обо мне

Анализирую данные и проверяю гипотезы: очищаю «грязные» выгрузки, считаю продуктовые метрики,
провожу A/B-тесты и пишу выводы, на которые бизнес может опереться. Стараюсь не останавливаться на
p-value: проверяю корректность эксперимента, размер эффекта и то, не создан ли результат артефактом в данных.

Сейчас двигаюсь в **Data Engineering** (ETL, хранилища, Airflow) и изучаю **Java-бэкенд** на Spring Boot.
Для души — железо на ESP32 и Arduino.

## Лучшие проекты

| Проект | Задача | Что нашёл |
|---|---|---|
| **[A/B-тест платёжной воронки](https://github.com/EfimovAN18/ab-payment-funnel-test)** | Внедрять ли новую воронку оплаты | Конверсия упала с 29,5% до 18,4%. Нашёл перекос групп (SRM) и перелом в середине теста — вероятный технический сбой |
| **[Длительность госпитализации](https://github.com/EfimovAN18/hospital-stay-analysis)** | Что влияет на срок лечения, 120 тыс. госпитализаций | Разница 3,5 дня между плановыми и экстренными пациентами оказалась артефактом одного отделения: без него — 0,7 дня |
| **[Туризм в регионах РФ](https://github.com/EfimovAN18/russia-tourism-analysis)** | Рынок турпакетов и средств размещения, 2018–2023 | Нашёл двойной учёт регионов в данных Росстата. Москва — 55% рынка турпакетов; внутренний туризм пережил пандемию без потерь |
| **[Яндекс Афиша](https://github.com/EfimovAN18/yandex-afisha-analytics)** | Анализ спроса на мероприятия | SQL + pandas + статистика и [дашборд в DataLens](https://datalens.yandex/so3p8ie2vmy6b/) |

## Все проекты

### 🧪 A/B-тесты и проверка гипотез

| Проект | Что внутри | Стек |
|---|---|---|
| [ab-payment-funnel-test](https://github.com/EfimovAN18/ab-payment-funnel-test) | A/B-тест платёжной воронки: SRM, кумулятивные метрики, z-тест, бутстреп | pandas, SciPy |
| [recommendation-ab-test-analysis](https://github.com/EfimovAN18/recommendation-ab-test-analysis) | Дизайн и анализ A/B-теста рекомендательного алгоритма | pandas, statsmodels |
| [sql-metrics-and-ab-testing](https://github.com/EfimovAN18/sql-metrics-and-ab-testing) | Активность пользователей Яндекс Книг и A/B-тест интерфейса | SQL, pandas |
| [hospital-stay-analysis](https://github.com/EfimovAN18/hospital-stay-analysis) | Длительность госпитализации: EDA и три гипотезы | pandas, SciPy |
| [russia-tourism-analysis](https://github.com/EfimovAN18/russia-tourism-analysis) | Туризм в регионах РФ: очистка данных Росстата, EDA, гипотезы | pandas, SciPy |
| [gofast-business-hypotheses](https://github.com/EfimovAN18/gofast-business-hypotheses) | Бизнес-гипотезы сервиса аренды самокатов | pandas, SciPy |

### 📊 Исследовательский анализ

| Проект | Что внутри | Стек |
|---|---|---|
| [yandex-afisha-analytics](https://github.com/EfimovAN18/yandex-afisha-analytics) | Спрос в Яндекс Афише + дашборд | SQL, pandas, DataLens |
| [road-accidents-analysis](https://github.com/EfimovAN18/road-accidents-analysis) | ДТП в Кировской и Московской областях: качество данных, динамика | pandas |
| [game-industry-preprocessing](https://github.com/EfimovAN18/game-industry-preprocessing) | Предобработка данных о видеоиграх 2000–2013 | pandas |

### 🗄️ SQL

| Проект | Что внутри |
|---|---|
| [aif-donors-cohort-analysis](https://github.com/EfimovAN18/aif-donors-cohort-analysis) | Когортный анализ благотворителей фонда: MAU, Retention, средний чек, LTV |
| [hhru-analyst-job-market-analysis](https://github.com/EfimovAN18/hhru-analyst-job-market-analysis) | Вакансии аналитиков на hh.ru |
| [donorsearch-data-analysis](https://github.com/EfimovAN18/donorsearch-data-analysis) | Активность доноров и планирование донаций |
| [darkwood-secrets-sql-analysis](https://github.com/EfimovAN18/darkwood-secrets-sql-analysis) | Монетизация и внутриигровые покупки |
| [real-estate-market-analysis](https://github.com/EfimovAN18/real-estate-market-analysis) | Рынок недвижимости Петербурга и Ленобласти |

### ⚙️ Разработка

| Проект | Что внутри | Стек |
|---|---|---|
| [cpp-task-manager](https://github.com/EfimovAN18/cpp-task-manager) | Консольный менеджер задач: приоритеты, дедлайны, поиск, сохранение, тесты | C++17, CMake, CTest |
| [orders-data-lab](https://github.com/EfimovAN18/orders-data-lab) | Работа с данными заказов | Python |
| [cpp-calculator](https://github.com/EfimovAN18/cpp-calculator) | Калькулятор | C++ |

## Стек

| | |
|---|---|
| **Анализ данных** | Python, pandas, NumPy, SciPy, statsmodels, Matplotlib, seaborn, Jupyter |
| **Статистика** | A/B-тесты, SRM, z- и t-тесты, Манн — Уитни, бутстреп, доверительные интервалы |
| **Базы и BI** | PostgreSQL, SQLite, Yandex DataLens |
| **Разработка** | Java, C++, C#, Git, CMake, Linux |
| **Изучаю** | Spring Boot, Docker, Apache Airflow, ClickHouse |

## Скоро

- ☕ REST API на Spring Boot + PostgreSQL + Docker
- 🔧 ETL-пайплайн на Airflow с хранилищем данных
