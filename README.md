# Football Players Forscast

## Predicting high potential players along with their wage/market price

This repository presents the tools and techniques used to analyze player data in order to uncover important patterns. These patterns are then leveraged to train a state-of-the-art Random Forest model for predicting high-potential players. A second Random Forest model is trained specifically to accurately predict player wages.

Tools and techniques used:

* Data preprocessing
* Exploratory Data Analysis (EDA)
* Feature engineering
* SMOTE (Synthetic Minority Over-sampling Technique)
* Hyperparameter tuning
* And more...

## Project Structure

```
Project/
│
├── FOOTBALL_PLAYERS_FORCAST/
│   ├── Data/
│   │   ├── final_data.csv     #Players stats used in Part 1.
│   │   └── players_3120.csv   #Players stats used in Part 2.
│   ├── Data_cleaning.ipynb    
│   ├── EDA.ipynb                 
│   ├── Feature_Engineering.ipynb             
│   ├── Football_player_value_predict.ipynb               
│   ├── Pre_EDA.ipynb                
│   └── RF_model.ipynb              
│  
└── README.md                  # This file
```

## Setup Instructions

- **Clone the Repository (if applicable):**
    ```bash
    git clone <repository-url>
    ```


## Part 1: Player Potential Analysis

* Data Cleaning: Removes unnecessary features and duplicate samples.

* Preparation for EDA: Creates columns for four player categories and new attributes for identifying high-potential players. Labels players accordingly.

* Exploratory Data Analysis (EDA): Explains the methodology behind defining high-potential players using data exploration techniques.

* Feature Engineering: Selects the most relevant features using a Random Forest classifier. The processed dataset is saved as final_data.csv.

* Model Training (RF 2): Trains the model on final_data.csv using three approaches: Baseline, SMOTE, and SMOTE with Hyperparameter Tuning.

## Part 2: Player Value Prediction

* football-player-value-predict: Integrates EDA, feature engineering, and model training using Random Forest on preprocessed data to predict player values.