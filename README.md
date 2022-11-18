# 주요주주 지분공시에 따른 주가 추이 예측
(2022.11.03~2022.11.18)
(group project 6)

### Raw_data
- all_ent.csv -> samsung.csv
- stock_code ->samsung_price.csv
- samsung.csv + samsung_price.csv -> weighted_data.csv, y_data.csv

### Library
- numpy, pandas
- scikit-learn, optuna, mlxtend, eli5

### Models

- scikit-learn
-   - [RandomForestClassifier, GradientBoostingClassifier, ExtraTreesClassifier]
- Xgboost
-   - XGBClassifier
- optuna
- mlxtend

```
.
├── 1_Preprocessing
│   ├── 1_equity_diisclosure_preprocessing.ipynb
│   ├── 2_stock_price_preprocessing.ipynb
│   └── 3_total_data_preprocessing.ipynb
├── 2_EDA
│   └── 1_EDA.ipynb
├── 3_Modeling
│   ├── 1_select_main_model.ipynb
│   ├── 2_parameter_tuning.ipynb
│   └── 2_parameter_tuning_colab.ipynb
├── 4_Presentation
│   └── _ppt.pdf
├── README.md
└── Data
    ├── Preprocessed_Data
    │   ├── X_data.csv
    │   ├── data_(main).csv
    │   ├── forEDA.csv
    │   ├── samsung.csv
    │   ├── samsung_price.csv
    │   ├── weighted_data.csv
    │   └── y_data.csv
    └── Raw_Data
        ├── all_ent.csv
        └── stock_code
            └── 005930.csv

8 directories, 18 files

```

#### Data

<img width="1728" alt="Screen Shot 2022-11-18 at 14 41 50" src="https://user-images.githubusercontent.com/112222918/202629549-cf946fb3-6e84-4907-ad3b-dc9b617b531e.png">

#### Data_setting
<img width="1728" alt="Screen Shot 2022-11-18 at 14 42 31" src="https://user-images.githubusercontent.com/112222918/202629671-7aad3bdb-84b2-47b1-aeba-4c362563db5c.png">

#### Modeling method
<img width="1728" alt="Screen Shot 2022-11-18 at 14 42 00" src="https://user-images.githubusercontent.com/112222918/202629652-c395083a-135e-4735-809c-cbb0ed16ab59.png">




#### Library versions
Package                                           Version
------------------------------------------------- -----------
eli5                                              0.13.0
numpy                                             1.23.3
optuna                                            3.0.3
pandas                                            1.5.0
scikit-learn                                      1.1.3
scipy                                             1.8.1
xgboost                                           1.7.1
