### [Прогнозирование оттока клиентов Банка](https://github.com/chusovalex/DataScienceProjects/blob/main/project_05/project_05_churn_model.ipynb)

**Задача проекта:**\
На основе данных из банка определить клиентов, которые могут уйти.

**Результаты:**
- Ознакомились с данными и подготовили их к исследованию: преобразовали категориальные признаки в численные с помощью техники прямого кодирования One-Hot Encoding;
- Исследовали баланс классов: классы оказались несбалансированы;
- Применили 4 способа борбы с дисбалансом - параметр class_weight, уменьшение выборки, увеличение выборки и изменение порога. Лучшие результаты показал метод борьбы с дисбалансом SMOTE;
- Достигли значения метрики f1 = 0.61 с помощью CatBoostClassifier


**Используемые инструменты:**\
Pandas, Pandas, Seaborn, Scikit-learn, CatBoost, imblearn

**Cтатус проекта:**\
Завершен
