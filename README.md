# Самостоятельный проект Яндекс.Практикум: Определение неэффективных операторов

## Задача

1. Проведите исследовательский анализ данных,
2. Определите неэффективных операторов,
3. Проверьте статистические гипотезы.

## Данные

- `user_id` — Идентификатор клиентского аккаунта в сервисе,
- `date` — Дата статистики,
- `direction` — Направление вызовов (out - исходящий вызов, in — входящий вызов),
- `internal` — Является ли звонок внутренним звонком между операторами клиента,
- `operator_id` — Идентификатор оператора,
- `is_missed_call` — Является ли звонок пропущенным,
- `calls_count` — Количество звонков,
- `call_duration` — Длительность звонка (без учета времени ожидания),
- `total_call_duration` — Длительность звонка (с учетом времени ожидания),
- `tariff_plan` — Текущий тарифный план клиента,
- `date_start` — Дата регистрации клиентв в сервисе.

## Используемые библиотеки
pandas, numpy, matplotlib.pyplot, plotly.express, seaborn, datetime, scipy, statistics
