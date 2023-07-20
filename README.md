# Titanic Survival Prediction Challenge

My take on the Titanic Survival Prediction Challenge. The challenge is to predict the survival (1 = survived, 0 = died) of passengers in the test dataset based on patterns found in the train dataset.

## Dataset

The dataset consists of two CSV files: `train.csv` and `test.csv`. The `train.csv` file contains the training data with known survival outcomes, whilst the `test.csv` file contains the data for which survival needs to be predicted.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Install the required packages using `pip`:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage

1. Clone this repository or download the code files.
2. Place the `train.csv` and `test.csv` files in the same directory as the code files.
3. Run the `titanic_machine_learning.py` script to preprocess the data, train the model and make predictions.
4. The predictions will be saved in a file named `submission.csv`.

## Code Overview

- `titanic_machine_learning.py`: The main script that loads and preprocesses the datasets, performs feature engineering and selection, tunes hyperparameters using GridSearchCV, trains a Random Forest Classifier, predicts survival for the test dataset and generates a submission file. Functions are then set out to visualise survival rates based on gender and age, as well as feature importance and the ROC curve.

## Visualisations

Various visualisations are generated to gain insights into the data and the model's performance. The visualisations include bar graphs for survival based on gender, a box plot for survival based on age, a correlation matrix and feature importance.

## Licence

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

This project is based on the Kaggle Titanic dataset and is part of a machine learning challenge. The code was developed for educational purposes and to practise data preprocessing, feature engineering and classification using Random Forests. Special thanks to the Kaggle community for providing the dataset and inspiring this project.
