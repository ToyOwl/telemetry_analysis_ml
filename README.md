
## Цель:

предсказать **RUL** время полезной работы оборудования до выхода его из строя.

## Набор данных:

https://www.kaggle.com/datasets/tiagotgoz/predictive-useful-life-based-into-telemetry

## Блокноты: 
- Telemetry Analysis and Datasets Preparation.ipynb EDA и дополнение новыми признаками tsfresh
- DecisionTreeRegression_for_RUL_Prediction.ipynb предсказание RUL моделью  DecisionTreeRegression
- XGBoost_for_RUL_Prediction.ipynb предсказание RUL ансамблевой моделью XGBoost при выполнение оптимизации гиперпараметров рекомендуется включить использование GPU в коллабе

## Данные:

- data/train_telemetry.csv -обогащенные новыми признаками обучающий набор данных
- data/test_telemetry.csv -обогащенные новыми признаками обучающий набор данных 
