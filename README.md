# Spaceship Titanic Machine Learning Workshop

This repository contains the source code and submission files for the AI3023 Machine Learning Workshop final project.

## Files
- `source_notebook.ipynb`: main notebook for preprocessing, feature engineering, model training, validation, ensembling, and submission generation.
- `submission_cat_main_050.csv`: final selected submission file.
- `submission_cat_main_bestT.csv`: threshold-tuned submission.
- `submission_cat_group_050.csv`: group-smoothed submission.
- `submission_cat_group_bestT.csv`: group-smoothed and threshold-tuned submission.

## How to Run
1. Download the Spaceship Titanic dataset from Kaggle.
2. Place `train.csv`, `test.csv`, and `sample_submission.csv` in the same folder as the notebook.
3. Install the required packages: pandas, numpy, matplotlib, seaborn, scikit-learn, catboost, lightgbm, and xgboost.
4. Run `source_notebook.ipynb` from top to bottom.
5. The notebook generates submission CSV files for Kaggle.

## Final Result
Best observed public leaderboard score: 0.81248  
Ranking snapshot: #248
