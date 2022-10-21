# Задачи проекта

- был проведен A/B тест: тестовой группе предлагалась новая модель оплаты коллекций шаблонов, контрольной – старая механика;
- проанализировать итоги эксперимента и решить, нужно ли выкатывать новую модель на остальных пользователей;
- использовать продуктовые метрики для оценки;
- при наличии различий объяснить, с чем они могут быть связаны и являются ли значимыми;
- создать дашборд для отлеживания вовлеченности пользователей.

# Результаты

- в качестве метрик для анализа были выбраны: CR, ARPU, ARPPU
- предварительный анализ показал различия в тестовой и контрольной группе (тестовая группа показывает лучшие результаты)
- использованы тест Манна-Уитни для оценки различий
- по результатам бутстрапа была отклонена нулевая гипотеза о равенстве выборок
- принято решение о внесении изменений на всех пользователей

![Иллюстрация к проекту](https://github.com/AlenaLes/A-B-test/blob/main/Dashboard%201.png)
