## Выбор локации для скважины
### Описание проекта
Интернет-магазин продаёт разные товары: для детей, для дома, мелкую бытовую технику, косметику и даже продукты. 
Отчёт магазина за прошлый период показал, что активность покупателей начала снижаться. 
Возможный выход — удерживать активность постоянных клиентов. Сделать это можно с помощью персонализированных предложений.

Нам предстоит разработать решение, которое позволит персонализировать предложения постоянным клиентам, чтобы увеличить их покупательскую активность, а именно, создать модель которая подскажеть на каких клиентов стоить обратить пристальное внимание и дать рекомендации по их удержанию, увеличению покупательской активности и росту прибыли интернет-магазина!
### Используемые библиотеки и инструменты
- NumPy
- Pandas
- Matplotlib
- Seaborn
- OneHotEncoder
- OrdinalEncoder
- StandardScaler
- MinMaxScaler
- RobustScaler
- ColumnTransformer
- SimpleImputer
- recall_score
- SVC
- make_classification
- shap
- LogisticRegression
- KNeighborsClassifier
- DecisionTreeClassifier
### Вывод
Мы сегментировали покупателей на 3 группы:

! ! ! - наиболее ценные клиенты, прибыль от которых более 4, и вероятность снижения более 0.6, то есть нам нужно как можно сильнее стараться их удержать

! ! - клиенты, которые приносят прибыль более 4, но вероятность снижения менее 0.6, так же стоит уделить им внимание, но меньше, поскольку они не стремятся уходить он нас к конкурентам

! - остальные клиенты, прибыль от которых менее 4, их мы можем порадовать какими-либо поадрками и акциями, но чисто символическими.

И сформировали некоторые предложения, которые можно рассмотреть для удержания самой важной для магаззина категории - ! ! !:
- релизовать скидочные программы в интересующих пользователей категориях;
- сделать персональные рассылки с купонами и спецпреложениями;
- рассмотреть возмоность бесплатного предоставления подписки преимум на небольшой срок, для стимулирования покупательской активности.