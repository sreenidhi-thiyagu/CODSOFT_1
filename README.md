# CODSOFT_1
Titanic Survival Prediction

This project demonstrates a simple Excel-based approach to predict whether a passenger on the Titanic survived or not. The dataset used contains information about individual passengers such as their age, gender, ticket class, fare, and survival status.

Dataset

The dataset includes the following features:

Survived: Target variable (1 = survived, 0 = did not survive).

Pclass: Ticket class (1st, 2nd, 3rd).

Sex: Gender of the passenger (male, female).

Age: Age of the passenger.

SibSp: Number of siblings/spouses aboard.

Parch: Number of parents/children aboard.

Fare: Ticket fare.

Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

Steps

Data Preparation

Cleaned the dataset using Excel by removing irrelevant columns (e.g., PassengerId, Name, Ticket, Cabin).

Handled missing values by filtering out rows with missing data.

Encoded categorical variables directly in Excel:

Sex: male = 0, female = 1.

Embarked: C = 0, Q = 1, S = 2.

Model Building

Leveraged Excel formulas and functions to preprocess the data.

Used external tools to implement logistic regression and generate predictions.

Results were validated and exported back to Excel for analysis.

Predictions

Predicted survival for the dataset.

Exported the results to an Excel file.

Files

titanic.csv: Input dataset containing passenger information.

titanic_predictions.xlsx: Output Excel file with actual and predicted survival statuses.

Requirements

Microsoft Excel or any compatible spreadsheet software.

Usage

Open the provided dataset in Excel.

Follow the documented steps in Excel to preprocess the data and apply formulas.

Use the generated output to analyze survival predictions.

Results

Using Excel, the data was analyzed and predictions were generated efficiently. Further analysis or modeling can be explored using other advanced tools if needed.

License

This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments

The dataset is made available by Kaggle's Titanic: Machine Learning from Disaster.
