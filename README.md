# bank-marketing

## Project Overview
***The company aims to optimize the cold-calling process within a marketing campaign focused on attracting clients to deposit products.
The goal is to predict whether a client will agree to open a deposit account after a phone call***

## Objective
To build a machine learning model that predicts client responses based on demographic and communication data, allowing the company to focus on high-potential clients and reduce unnecessary call.

## Methods
- **EDA:** exploring and visualizing data
- **Feature preprocessing:** encoding of categorical features, scaling of numerical features
- **Finding the Best Model:** Linear, Metric, Ensembles, and Neural Networks
- **Model used:** CatBoostClassifier
- **Model metrics:** Presicion-Recall-AUC, Roc-AUC, Precision, Recall, F1-score
- **Business metrics:** Conversion, Profit, Lift Analysis(Decile analysis)
- **Optimal probability threshold:** 0.1 (maximized Recall)

## Results
 - **Conversion rate increased from 12% -> 27%**
 - **Profit grew from €96,757 -> €100,656**
 - **Top 10% of clients show 65% conversion, which is 5.5× higher than average**
 - **The model demonstrates strong ranking capability, enabling operators to focus on the most promising clients**

## Conclusion
***The predictive model improves marketing efficiency and profitability, allowing for a more data-driven and resource-effective approach.***


## Описание проекта
***Компания стремится оптимизировать процесс холодных звонков в рамках маркетинговой кампании по привлечению клиентов к депозитным продуктам.
Цель - предсказать, согласится ли клиент открыть депозит после телефонного звонка.***

## Цель
Построить модель машинного обучения, которая по данным о клиенте предсказывает вероятность отклика, чтобы сосредоточить усилия операторов на наиболее перспективных клиентах и сократить количество звонков.

## Методы
- **Анализ данных:** изучение и визуализация данных
- **Обработка признаков:** кодирование категориальных и масштабирование числовых признаков
- **Поиск лучшей модели:** линейные, метрические, ансамбли и нейросети
- **Используемая модель:** CatBoostClassifier
- **Метрики модели:** Presicion-Recall-AUC, Roc-AUC, Precision, Recall, F1-score
- **Бизнесс метрики:** Конверсия, Прибыль, Анализ эффективности ранжирования
- **Оптимальный порог вероятности:** 0.1 (максимизирует Recall)

## Результаты
**Конверсия выросла с 12% до 27%**
**Прибыль увеличилась с 96 757 € до 100 656 €**
**В топ-10% клиентов конверсия достигает 65%, что в 5.5 раза выше среднего**
**Модель хорошо ранжирует клиентов и помогает операторам сосредоточиться на самых перспективных**

## Вывод
***Внедрение модели позволяет значительно повысить эффективность и прибыльность маркетинговой кампании, делая её более ориентированной на данные и экономичной по ресурсам.***
