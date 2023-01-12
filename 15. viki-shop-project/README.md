**Проект для «Викишоп»**

Интернет-магазин «Викишоп» запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других.

**Цель:**

- Нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.
- Необходимо обучить модель классифицировать комментарии на позитивные и негативные и постройть модель со значением метрики качества F1 не меньше 0.75.

**Выводы проекта:**

- Логистическая регрессия выдает на тестовой выборке результат F1-score: 0.788, у LGBM: 0.782. 
- Обе модели хороши, но все таки у логистической регрессии лучший результат.

**Стек:**

pandas, numpy, sklearn, re, nltk, tqdm, lightgbm, catboost, time, plotly

**Статус проекта:**

Завершен.