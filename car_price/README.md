## Определение стоимости автомобилей
### Описание проекта
Сервис по продаже автомобилей с пробегом разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. В нашем распоряжении исторические данные: технические характеристики, комплектации и цены автомобилей. Нам нужно построить модель для определения стоимости.

Заказчику важны:
качество предсказания;
скорость предсказания;
время обучения.
### Используемые библиотеки и инструменты
- NumPy
- Pandas
- Matplotlib
- Seaborn
- sklearn.model_selection/train_test_split, GridSearchCV, RandomizedSearchCV, cross_val_score
- sklearn.pipeline/Pipeline
- sklearn.preprocessing/OneHotEncoder, OrdinalEncoder, StandardScaler, MinMaxScaler
- sklearn.compose/ColumnTransformer
- sklearn.imput/SimpleImputer
- sklearn.preprocessing/LabelEncoder
- sklearn.linear_model/LinearRegression, LogisticRegression
- sklearn.tree/DecisionTreeRegressor
- sklearn.ensemble/RandomForestRegressor
- CatBoostRegressor
- LGBMRegressor
- sklearn.metrics/root_mean_squared_error, mean_squared_error, make_scorer
