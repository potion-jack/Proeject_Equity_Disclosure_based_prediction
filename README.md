# 주요주주 지분공시에 따른 주가 추이 예측

### raw_data
- all_ent -> samsung
- stock_code ->samsung_price

- samsung + samsung_price -> weighted_data, y_data

### models

- scikit-learn
-   - [RandomForestClassifier(), GradientBoostingClassifier(), ExtraTreesClassifier()]
- Xgboost
-   - XGBClassifier
- optuna
- mlxtend

```
.
├── 1_preprocessing
│   ├── 1_equity_diisclosure_preprocessing.ipynb
│   ├── 2_stock_price_preprocessing.ipynb
│   └── 3_total_data_preprocessing.ipynb
├── 2_EDA
│   └── 1_EDA.ipynb
├── 3_modeling
│   ├── 1_select_main_model.ipynb
│   ├── 2_parameter_tuning.ipynb
│   └── 2_parameter_tuning_colab.ipynb
├── 4_presentation
├── README.md
└── data
    ├── preprocessed_data
    │   ├── X_data.csv
    │   ├── data_(main).csv
    │   ├── forEDA.csv
    │   ├── samsung.csv
    │   ├── samsung_price.csv
    │   ├── weighted_data.csv
    │   └── y_data.csv
    └── raw_data
        ├── all_ent.csv
        └── stock_code
            └── 005930.csv

8 directories, 17 files

```
