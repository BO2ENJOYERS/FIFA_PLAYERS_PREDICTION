# FIFA_PLAYERS_PREDICTION
Sequence of notebook usage:
**Part 1: Player Potential Analysis**

    Data Cleaning: Removes unnecessary features and duplicate samples.

    Preparation for EDA: Creates columns for four player categories and new attributes for identifying high-potential players. Labels players accordingly.

    Exploratory Data Analysis (EDA): Explains the methodology behind defining high-potential players using data exploration techniques.

    Feature Engineering: Selects the most relevant features using a Random Forest classifier. The processed dataset is saved as final_data.csv.

    Model Training (RF 2): Trains the model on final_data.csv using three approaches: Baseline, SMOTE, and SMOTE with Hyperparameter Tuning.

**Part 2: Player Value Prediction**

    football-player-value-predict: Integrates EDA, feature engineering, and model training using Random Forest on preprocessed data to predict player values.