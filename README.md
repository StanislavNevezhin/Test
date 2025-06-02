### Добро пожаловать! 👋

+++

Я Станислав Невежин, кандидат технических наук, Data и BI-аналитик 📚.

Более 10 лет я занимаюсь анализом, разработкой и внедрением новых технологических процессов и решений для крупнейших отечественных и зарубежных компаний.

↪️✌️ Мое резюме можно найти [тут](https://hh.ru/resume/58d05c8eff085992270039ed1f5675414e5648) 

📩 Буду рад пообщаться в [Telegram](https://t.me/Stanislav_Nevezhin) и по почте [snevevzhin@gmail.com](mailto:snevevzhin@gmail.com)   

**Hard Skills**:   1) SQL - MySQL, PostgreSQL, DBeaver;
2) BI - Microsoft Power BI, Tableau;
3) Python:
Base - Pandas, Numpy, SciPy;
Visualization - Matplotlib, Seaborn, Plotly;
ML - Scikit-Learn, LightGBM, XGBoost, Catboost, LAMA;
DL - TensorFlow, Keras, PyTorch;
PROD - Streamlit, Flask;
DE - Docker, Hadoop, Hive, PySpark, Linux, Git, Heroku.

**Soft Skills**:
- Умение строить гипотезы, проводить исследования и визуализировать данные/полученные результаты;
- Навыки командной работы как в качестве руководителя проекта, так и исполнителя;
- Умение работать в режиме многозадачности;
- Желание и готовность развиваться в сфере анализа данных.

**Kaggle**: https://www.kaggle.com/stanislavnevezhin

## Финальный проект
| Название проекта | Описание | Стек и инструменты |
| :--- | --- | --- |
| [Финальный проект](https://github.com/StanislavNevezhin/Data-Analytics/tree/main/PROJECT_final) | Исследование временных рядов основных котировок крупных корпораций - Apple, Microsoft, Google, nVidia. Запуск наилучшего инференса модели в качестве сервиса | **sklearn.linear_model** (LinearRegression), **sklearn.ensemble** (AdaBoostRegressor, GradientBoostingRegressor, VotingRegressor), **sklearn.model_selection** (GridSearchCV, TimeSeriesSplit, cross_val_score), **sklearn.metrics** (mean_absolute_percentage_error, mean_squared_error, r2_score), **statsmodels.tsa** (seasonal, arima.model, stattools.adfuller), **statsmodels.graphics.tsaplots** (plot_acf, plot_pacf), **Catboost** (CatBoostRegressor), **prophet** (Prophet), **statsmodels.tsa** (seasonal, arima.model, stattools.adfuller), **statsmodels.graphics.tsaplots** (plot_acf, plot_pacf), **pmdarima** (auto_arima), **seaborn** (lineplot, pairplot, heatmap), **with** statement, time series, AIC, concat, correlation matrix, cross validation, correlogram, datetime, EDA, feature engineering, os.path, resample, rolling, stationarity, SMA, ARIMA, GPU, yfinance, pickle, Docker, Dockerfile, Flask |


## Проекты
| Название проекта | Описание | Стек и инструменты |
| :--- | --- | --- |
| [Проект 1. Анализ резюме из HeadHunter](https://github.com/StanislavNevezhin/Data-Analytics/tree/main/PROJECT-1) | Подготовка первичных данных - базы резюме, выгруженной с сайта поиска вакансий HH.ru - для построения перспективной модели, автоматически определяющей уровень заработной платы, подходящей пользователю, исходя из информации, которую он указал о себе | **plotly** (histogram, box, bar, imshow, scatter, sunburst), **seaborn** (histplot), os.path, merge, EDA, feature engineering |
| [Проект 2. Анализ резюме из HeadHunter (SQL)](https://github.com/StanislavNevezhin/Data-Analytics/tree/main/PROJECT-2) | Анализ данных - базы резюме, выгруженной с сайта поиска вакансий HH.ru, используя навыки написания запросов SQL в БД PostgreSQL - для построения модели, рекомендующей вакансии клиентам агентства, претендующим на позицию Data Scientist | psycopg2, requests, **plotly** (bar, imshow), **with** statement, **try-except** statement, concat, EDA, feature engineering |
| [Проект 3. Рейтинг отеля по данным сайта Booking. Соревнование на Kaggle](https://github.com/StanislavNevezhin/Data-Analytics/tree/main/PROJECT-3) | Построение модели, предсказывающей рейтинг отеля | **collections** (OrderedDict), **category_encoders** (TargetEncoder), **sklearn.model_selection** (train_test_split), **sklearn.feature_selection** (chi2, f_classif), **sklearn.ensemble** (RandomForestRegressor), **sklearn.metrics** (mean_absolute_error, mean_absolute_percentage_error), **sklearn.preprocessing** (MinMaxScaler), concat, correlation matrix, EDA, feature engineering, feature importance, **seaborn** (barplot, boxplot, heatmap), lightautoml, **nltk** (SentimentIntensityAnalyzer), pivot_table, regex |
| [Проект 4. Задача классификации](https://github.com/StanislavNevezhin/Data-Analytics/tree/main/PROJECT-4) | Построение модели машинного обучения, которая на основе предложенных характеристик клиента будет предсказывать поведение клиента при открытии депозита | **sklearn.metrics** (classification_report), **sklearn.preprocessing** (LabelEncoder, MinMaxScaler), **sklearn.model_selection** (train_test_split, GridSearchCV, cross_val_score), **sklearn.feature_selection** (SelectKBest), **sklearn.linear_model** (LogisticRegression), **sklearn.tree** (DecisionTreeClassifier), **sklearn.ensemble** (RandomForestClassifier, GradientBoostingClassifier), **optuna** (Trial, study), **match-case** statement, concat, cross validation, correlation matrix, EDA, feature importance |
| [Проект 5. Задача регрессии](https://github.com/StanislavNevezhin/Data-Analytics/tree/main/PROJECT-5) | Построение модели машинного обучения, которая на основе предложенных характеристик клиента будет предсказывать время поездки такси | **collections** (OrderedDict), **scipy.stats** (normaltest), **sklearn.cluster** (KMeans), **sklearn.metrics** (mean_squared_error, median_absolute_error), **sklearn.preprocessing** (OneHotEncoder, MinMaxScaler), **sklearn.model_selection** (train_test_split), **sklearn.feature_selection** (SelectKBest), **sklearn.linear_model** (LinearRegression, Ridge), **sklearn.tree** (DecisionTreeRegressor), **sklearn.ensemble** (RandomForestRegressor, GradientBoostingRegressor), **seaborn** (histplot, boxplot, scatterplot, lineplot, heatmap, barplot), **match-case** statement, swifter, os.system, os.path, gdown, XGBoost, merge, concat, EDA, feature engineering, feature importance |
| [Проект 6. Задача кластеризации](https://github.com/StanislavNevezhin/Data-Analytics/tree/main/PROJECT-6) | Построение модели кластеризации клиентов на основе их покупательской способности, частоты заказов и срока давности последней покупки, идентификация покупательского профиля каждого из кластеров | **sklearn.model_selection** (train_test_split, GridSearchCV), **sklearn.metrics** (silhouette_score, calinski_harabasz_score, davies_bouldin_score, accuracy_score), **sklearn.preprocessing** (MinMaxScaler, StandardScaler), **sklearn.pipeline** (Pipeline), **sklearn.ensemble** (RandomForestClassifier, GradientBoostingClassifier), **sklearn.cluster** (KMeans, AgglomerativeClustering), **sklearn.mixture** (GaussianMixture), **sklearn.decomposition** (PCA, explained_variance_ratio_), **sklearn.manifold** (TSNE, kl_divergence_), **seaborn** (barplot, scatterplot, lineplot), **plotly** (box, Scatterpolar), **match-case** statement, recursion, gdown, os.path, EDA, feature engineering, pivot_table, regex |


:arrow_up:[вверх ↑](https://github.com/StanislavNevezhin)

## Практические работы
| Название проекта | Описание | Стек и инструменты |
| :--- | --- | --- |
| [Проект 0.1. PYTHON. Инструменты для Data Science](https://github.com/StanislavNevezhin/Data-Analytics/tree/main/PROJECT-0.1) | Реализация алгоритма самого быстрого перебора чисел и угадывание загаданное компьютером число за минимальное количество попыток.<br/>Отработка навыков взаимодействия с Git-Github, настройка **.gitignore**, импорт собственных модулей python в Jupyter | Jupyter, import, git, python, gitignore |
| [Проект 0.2. PYTHON. Визуализация данных](https://github.com/StanislavNevezhin/Data-Analytics/tree/main/PROJECT-0.2) | Выяснение основных причин оттока клиентов и анализирование, чем ушедшие клиенты отличаются от лояльных и как между собой связаны различные признаки, определяющие клиентов. Подготовка рекомендаций к отчёту для банка, разрабатывающего кампанию лояльности по удержанию клиентов | **plotly** (pie, box, histogram, scatter, sunburst, bar, choropleth), **seaborn** (heatmap), pivot_table, EDA, feature engineering |
| [Проект 0.3. EDA. Статистические тесты](https://github.com/StanislavNevezhin/Data-Analytics/tree/main/PROJECT-0.3) | Выполнение статических тестов, проверка данных на нормальность и на наличие взаимосвязи | **scipy.stats** (shapiro, normaltest, pearsonr, spearmanr, ttest_ind, mannwhitneyu, ranksums), **seaborn** (kdeplot, heatmap), **statistics** (median), concat, correlation matrix, EDA, p-value |
| [Проект 0.4. EDA. A/B-тестирование](https://github.com/StanislavNevezhin/Data-Analytics/tree/main/PROJECT-0.4) | Анализ эффективности вариантов посадочной страницы в туристической компании | **statsmodels.stats.proportion** (proportions_ztest), **scipy.stats** (norm.ppf, t.ppf, shapiro, ttest_ind), **seaborn** (lineplot, heatmap), pivot_table, correlation matrix, EDA, feature engineering, cumsum, cumulative metrics, p-value, confidence intervals |
| [Проект 0.5. EDA. Проектирование экспериментов](https://github.com/StanislavNevezhin/Data-Analytics/tree/main/PROJECT-0.5) | Взаимодействие с платформой Comet.ml, логирование экспериментов | **sklearn.preprocessing** (MinMaxScaler), **sklearn.linear_model** (LogisticRegression), **sklearn.metrics** (accuracy_score), **category_encoders** (OneHotEncoder, BinaryEncoder), **seaborn** (heatmap, countplot), **comet_ml** (Experiment), concat, API kaggle |
| [Проект 0.6. ML. Обучение с учителем: классификация](https://github.com/StanislavNevezhin/Data-Analytics/tree/main/PROJECT-0.6) | Построение модели - классификатора, позволяющей своевременно определять уходящих клиентов банка, оценка качества построенных моделей | **sklearn.metrics** (f1_score, classification_report, recall_score, precision_score, accuracy_score), **sklearn.preprocessing** (MinMaxScaler, PolynomialFeatures), **sklearn.linear_model** (LogisticRegression), **sklearn.tree** (DecisionTreeClassifier), **sklearn.ensemble** (RandomForestClassifier), **sklearn.model_selection** (train_test_split), **seaborn** (barplot), EDA, feature engineering |
| [Проект 0.7. ML. Отбор и селекция признаков](https://github.com/StanislavNevezhin/Data-Analytics/tree/main/PROJECT-0.7) | Построение модели линейной регресии, предсказывающей стоимость автомобиля, оценка качества построенных моделей | **sklearn.metrics** (mean_absolute_error, mean_absolute_percentage_error, mean_squared_error, r2_score), **sklearn.linear_model** (LinearRegression), **sklearn.model_selection** (train_test_split), **sklearn.feature_selection** (RFE, SelectKBest, f_regression), feature engineering, wget |
| [Проект 0.8. ML. Отбор и селекция признаков](https://github.com/StanislavNevezhin/Data-Analytics/tree/main/PROJECT-0.8) | Построение модели классификации пользователей и определение лучшего способа кодирования данных в процессе подготовки данных. Закрепление Comet.ML на практике, логирование экспериментов | **sklearn.metrics** (accuracy_score, confusion_matrix, roc_curve, roc_auc_score), **sklearn.preprocessing** (OneHotEncoder, LabelEncoder), **sklearn.linear_model** (LogisticRegression), **comet_ml** (Experiment), wget, EDA, feature engineering, TP, FP, TN, FN |
| [Проект 0.9. ML. Оптимизация гиперпараметров модели](https://github.com/StanislavNevezhin/Data-Analytics/tree/main/PROJECT-0.9) | Построение моделей, предсказывающих биологический ответ молекул по их химическому составу, подбор гиперпараметров моделей | **sklearn.metrics** (f1_score), **sklearn.linear_model** (LogisticRegression), **sklearn.ensemble** (RandomForestClassifier), **sklearn.model_selection** (train_test_split, cross_validate, GridSearchCV, RandomizedSearchCV, cross_val_score), **hyperopt** (hp.choice, hp.uniform, space_eval), **optuna** (Trial, study), **seaborn** (countplot), **try-except** statement, cross validation, EDA |
| [Проект 0.10. MATH_ML. Линейная алгебра в контексте линейных методов](https://github.com/StanislavNevezhin/Data-Analytics/tree/main/PROJECT-0.10) | Построение регрессионной модели, прогнозирующей выработку газа на скважине на основе остальных характеристик скважины, и интерпретация результатов - рекомендации владельцу скважины | **collections** (OrderedDict), **sklearn.metrics** (mean_absolute_percentage_error), **sklearn.preprocessing** (StandardScaler, PolynomialFeatures), **sklearn.linear_model** (LinearRegression, Lasso, Ridge, ElasticNet), **sklearn.model_selection** (cross_validate, cross_val_score), **optuna** (Trial, study), **seaborn** (histplot, regplot, heatmap), **numpy.linalg** (norm, matrix_rank, det, inv), **numpy** (column_stack, hstack, corrcoef, printoptions, ones_like, ones, triu), **with** statement, **match-case** statement, correlation matrix, cross validation, EDA, feature engineering, SQLite, regularization L1-L2 |
| [Проект 0.11. MATH_ML. Математический анализ в контексте задачи оптимизации](https://github.com/StanislavNevezhin/Data-Analytics/tree/main/PROJECT-0.11) | Реализация алгоритмов координатного спуска и стохастического градиентного спуска, оценка качества полученных моделей | **sklearn.metrics** (mean_squared_error, mean_absolute_error), **sklearn.linear_model** (LinearRegression), **numpy.linalg** (norm), **numpy** (hstack, ones, zeros, std, append, full, inf), os.path |
| [Проект 0.12. MATH_ML. Наивный байесовский классификатор](https://github.com/StanislavNevezhin/Data-Analytics/tree/main/PROJECT-0.12) | Реализация классификатора спам-сообщений, подбор гиперпараметра модели | **sklearn.metrics** (classification_report, roc_curve), **sklearn.model_selection** (train_test_split, GridSearchCV), **sklearn.naive_bayes** (ComplementNB), **sklearn.feature_extraction** (text.CountVectorizer), **seaborn** (countplot, lineplot), **numpy** (nan), EDA, feature engineering, regex |
| [Проект 0.13. MATH_ML. Временные ряды](https://github.com/StanislavNevezhin/Data-Analytics/tree/main/PROJECT-0.13) | Анализ ВВП африканской страны Гана, расчёт волатильности, подбор гиперпараметров временных моделей | **sklearn.linear_model** (LinearRegression), **sklearn.model_selection** (GridSearchCV, TimeSeriesSplit), **sklearn.metrics** (mean_absolute_error, mean_absolute_percentage_error, mean_squared_error, r2_score), **statsmodels.tsa** (seasonal, arima.model, stattools.adfuller), **statsmodels.graphics.tsaplots** (plot_acf, plot_pacf), **pmdarima** (auto_arima), **arch.univariate** (arch_model), **seaborn** (lineplot), time series, AIC, MASE, correlogram, gdown, os.path, cross validation, EDA, rolling, interpolation, stationarity, SMA, ARIMA, GARCH |

:arrow_up:[вверх ↑](https://github.com/StanislavNevezhin/StanislavNevezhin/)

## Лицензия

<!-- Shield:  -->
[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

<!-- This work is licensed under a -->
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg


Add line
