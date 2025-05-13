Описание задачи:
Разработать решение, которое позволит персонализировать предложения постоянным клиентам, чтобы увеличить их покупательскую активность.

Используемые модели:
- DecisionTreeClassifier
- KNeighborsClassifier
- LogisticRegression
- SVC

Исходя из подбора гиперпараметров, лучшей моделью признана LogisticRegression.
Метрика лучшей модели на кросс-валидации: 0.899.
Параметры лучшей модели: {'preprocessor__num': StandardScaler(), 
			  'models__C': 4, 
			  'models': LogisticRegression(penalty='l1', random_state=42, solver='liblinear')}
