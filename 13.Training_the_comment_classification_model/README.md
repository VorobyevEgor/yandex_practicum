# Проект № 13: 
Обучение модели классификации комментариев

## Задачи проекта:
Определение токсичности комментариев.

## Описание проекта:
Интернет-магазин запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах.
То есть клиенты предлагают свои правки и комментируют изменения других.
Требуется инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.

## Сфера и направление деятельности компаний:
Интернет-сервисы, Стартапы, NLP, Машинное обучение

## Навыки и инструменты, применяемые в проекте:
**Pandas, Python, nltk, tf-idf**

### Краткий вывод:

С помощью предоставленного набора данных с разметкой о токсичности правок, мы смогли проанализировать и предобработать датафрейм. В нем было 159291 комментариев, из которых только 10% положительных. С помощью лемметизации, очистки текста от лишних символов и стоп-слов, а так же балансировки классов мы подобрали лучшую модель LogisticRegression, со значением метрики качества F1 на тестовой выборке равной 0,777. Таким образом выполнили поставленную задачу: Постройть модель со значением метрики качества F1 не меньше 0.75. 
