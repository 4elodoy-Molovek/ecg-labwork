# Лабораторная работа. Классификация ЭКГ

Вариант 1: определение меток `NORM` и `AFIB` по 12-канальной ЭКГ длительностью 10 секунд из PTB-XL. Разбиение выполнено по пациентам.

1. [Сборка датасета](ecg-warehouse/notebooks/lab_dataset.ipynb)
2. [Обучение и оценка классификатора](ecg-ml/notebooks/lab_training.ipynb)

Для воспроизведения поместите ZIP-архив [PTB-XL 1.0.3](https://physionet.org/content/ptb-xl/1.0.3/) в `ecg-warehouse/data/ptb-xl.zip`. Выполните `uv sync` отдельно в `ecg-warehouse` и `ecg-ml`. Запустите оба ноутбука по порядку, каждый в окружении своего проекта. Первый ноутбук создаёт датасет в `ecg-ml/data/`, второй читает его оттуда.

[Задание](https://gitverse.ru/unn-aicenter/ecg-labwork). Исходные проекты: [ecg-warehouse](https://gitverse.ru/unn-aicenter/ecg-warehouse) и [ecg-ml](https://gitverse.ru/unn-aicenter/ecg-ml).
