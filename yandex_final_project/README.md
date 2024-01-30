# Прогнозирование оттока клиентов

[ipynb](https://github.com/Blareed/yandex_ds_projects/blob/51288352bf5991f423711ce479270b48fc8ec4d3/yandex_final_project/%D0%B8%D1%82%D0%BE%D0%B3%D0%BE%D0%B2%D1%8B%D0%B9%20%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%20yandex.ipynb)

## Описание проекта

Требуется подготовить прототип модели машинного обучения, которая должна определять уйдет клиент или останется. Если выяснится, что пользователь планирует уйти, ему будут предложены промокоды и специальные условия.




## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **scipy**
- sklearn.model_selection.**GridSearchCV**
- sklearn.preprocessing.**OneHotEncoder, OrdinalEncoder, StandardScaler**
- sklearn.linear_model.**LogisticRegression**
- sklearn.tree.**DecisionTreeClassifier**
- sklearn.ensemble.**RandomForestClassifier, GradientBoostingClassifier**
- **matplotlib**

## 

## Общий вывод

Было обучено четыре различные модели с использованием методов машинного обучения, включая `LogisticRegression`, `RandomForestClassifier, CatBoostClassifier` и `GradientBoostingClassifier`. Обучение проводилось с использованием пайплайнов и метода `GridSearchCV` для подбора гиперпараметров. Модели были оценены по метрике `ROC AUC`.
