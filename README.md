## Реализация классификатора отзывов при помощи NLP-модели

Асташов И.В., 2024.


## Цель и задачи

**Цель**: Реализовать конвейер (до)обучения трансформерной NLP-модели для задачи бинарной классификации показателя
Recommended IND (рекомендует ли клиент продукт или нет) с помощью модели предоставленной на hugginface hub.


**Задачи**:

1. Загрузить и предобработать данные, включая удаление стоп-слов, лемматизацию текста, токенизацию и т.д;
2. Обучить модель T5 и оценить её качество на тестовой выборке;
3. Подобрать оптимальные гиперпараметры модели для улучшения ее качества;
4. Вычислить метрику F1 для оценки качества модели на тестовой выборке.

## Результаты

- Модель T5 показала F1 на тестовой выборке примерно 0.75;

## Выводы

- Для улучшения качества модели T5 можно провести более тщательную оптимизацию гиперпараметров и использовать дополнительные признаки, добавить наименование товара в текст отзыва, 
попробовать модель DistilBERT.