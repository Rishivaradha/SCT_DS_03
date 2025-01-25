Titanic Survival Prediction using Decision Tree Classifier

Project Overview

This project involves building a decision tree classifier to predict whether a passenger survived the Titanic disaster based on their demographic and behavioral data. The dataset used for this project is the Titanic dataset, which contains information about passengers, including their class, age, sex, fare, family size, and embarkation port.

Dataset

The dataset includes the following columns:

PassengerId: Unique identifier for each passenger.
Survived: Target variable (1 = survived, 0 = did not survive).
Pclass: Passenger class (1, 2, or 3).
Name: Name of the passenger.
Sex: Gender of the passenger (male or female).
Age: Age of the passenger.
Ticket: Ticket number.
Fare: Amount paid for the ticket.
Cabin: Cabin number.
Embarked: Port of embarkation (Southampton, Cherbourg, or Queenstown).
FamilySize: Number of family members aboard the Titanic.
Project Steps

1. Data Preprocessing
Handle missing values in columns like Age and Cabin.
Encode categorical variables such as 'Sex' and 'Embarked' into numerical values.
Scale numerical features like Age and Fare for better model performance.
2. Model Building
Split the dataset into training and testing sets.
Train a decision tree classifier on the training data to predict the survival of passengers.
3. Model Evaluation
Evaluate the model's performance using metrics such as accuracy, precision, recall, and F1-score.
Visualize the decision tree to understand the model's decision-making process.
4. Hyperparameter Tuning
Optimize the decision tree by adjusting hyperparameters like maximum depth, minimum samples per leaf, and others to prevent overfitting and improve generalization.
5. Prediction
Use the trained model to predict whether a passenger survived based on their demographic and behavioral data.
Expected Outcome

By the end of this project, the decision tree classifier will be able to predict whether a passenger survived the Titanic disaster with reasonable accuracy based on their demographic and behavioral characteristics.

