# 🚗 Проект: Прогноз стоимости автомобилей

## 📦 Данные

В датасете содержится информация о **500 000** объявлениях по продаже автомобилей. Примеры признаков:

- **🗺️ География**: `region`, `state`, `county`, `lat`, `long`
- **🚘 Технические характеристики**: `year`, `manufacturer`, `model`, `cylinders`, `condition`, `fuel`, `odometer`, `drive`, `type`, `paint_color`
- **📄 Прочее**: `title_status`, `description`, `posting_date`
- **🎯 Целевой признак**: `price` — цена автомобиля (задача регрессии)

## 🎯 Задача

Построить модель машинного обучения, которая сможет предсказывать стоимость автомобиля по его описанию и характеристикам.

## 📊 Результат

- **🔝 Лучшая модель**:
  - ML: `XGBRegressor`
  - DL: `Sequential (Dense → Dense → Dense)`
- **📈 Метрики на тесте**:
  - `XGBRegressor`:  
    - **MAE**: 4267.41  
    - **RMSE**: 6169.61  
    - **R²**: 0.7614
- **🧠 Использованные подходы**:
  - Классические ML-модели: `RandomForest`, `XGBoost`, `LGBM`, `CatBoost`
  - Нейросеть: `MLP` (2 скрытых слоя, `ReLU`, `MSE`)

## 📚 Используемые библиотеки

*pandas | numpy | matplotlib | seaborn | scikit-learn | catboost | xgboost | lightgbm | tensorflow | keras*
