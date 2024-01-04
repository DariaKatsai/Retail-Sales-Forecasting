# Прогнозування Прибутку в Роздрібній Торгівлі

## Опис проекту
Цей проект зосереджений на аналізі даних роздрібних продажів з метою прогнозування прибутку. Використовуючи техніки машинного навчання та аналізу часових рядів, проект має на меті визначити ключові фактори, які впливають на продажі, та розробити модель для прогнозування майбутнього прибутку.

## Завдання проекту
- Відфільтрувати та обробити дані з датасету роздрібних продажів.
- Розробити функції для генерації ознак, що враховують сезонність, святкові дні, та інші фактори.
- Використати алгоритм XGBoost для побудови моделі прогнозування прибутку.
- Оцінити якість моделі за допомогою метрик, таких як RMSE.

## Дані
Для аналізу використовується датасет 'Online Retail II', який містить дані про роздрібні продажі. Датасет можна завантажити за наступним посиланням: [Online Retail II Data Set](https://archive.ics.uci.edu/dataset/502/online+retail+ii).

## Результати
Модель була навчена та протестована на даних, що включають різні фактори, які можуть впливати на продажі. Результати тестування моделі показали, що RMSE (Root Mean Square Error) складає 9.51, що вказує на точність моделі у прогнозуванні прибутку.
