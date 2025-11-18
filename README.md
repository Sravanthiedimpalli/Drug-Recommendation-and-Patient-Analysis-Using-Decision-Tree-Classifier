# Drug Recommendation and Patient Analysis Using Decision Tree Classifier 💊🩺

## Overview

This project explores a drug prescription dataset with 200 patient records and 6 features (age, sex, blood pressure, cholesterol, Na-to-K ratio, and prescribed drug class). Data was analyzed and visualized using Python (pandas, matplotlib), and various data preprocessing steps such as encoding categorical variables and scaling were applied. A Decision Tree Classifier was trained to predict the appropriate drug class for new patients using their health attributes.

## Key Steps

- Data cleaning, exploration, and summary statistics (missing/duplicate check, describe, data types)
- Encoding categorical patient information and scaling features
- Decision Tree model training, evaluation (accuracy and F1 score), and hyperparameter tuning
- Visualization of decision tree and analysis of feature importances
- Model cross-validation and insights into drug prescription patterns

## Major Insights

- Achieved high accuracy and F1 score (up to 97%) in drug class prediction
- Age and Na-to-K ratio were the most influential features in model decisions
- Clear patterns emerged for certain drugs being frequently prescribed for specific combinations of patient factors

## How to Run

1. Download or clone this repository and place the dataset (`drug200.csv`) in your working directory.
2. Open the `IDT2.ipynb` notebook in Jupyter or Google Colab.
3. Run cells sequentially to reproduce data analysis, modeling, and results.

## Tools Used

- Python (Jupyter Notebook)
- pandas
- numpy
- matplotlib
- scikit-learn

## Conclusion
This project demonstrated effective use of data analysis and machine learning to automate drug prescription recommendations based on patient parameters. The Decision Tree Classifier achieved high predictive accuracy, with age and Na-to-K ratio being most influential in decisions. These results highlight the potential of interpretable AI models to support clinical decision-making and optimize patient treatment strategies. 

