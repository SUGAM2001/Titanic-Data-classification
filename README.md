# Titanic-Classification

# Description About The Dataset
The sinking of the Titanic is one of the most infamous shipwrecks in history.

On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone on board, resulting in the death of 1502 out of 2224 passengers and crew.

While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

In this challenge, we ask you to build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).

Download the dataset from - https://www.kaggle.com/datasets/yasserh/titanic-dataset
Titanic dataset contains 891 rows and 12 columns. The columns are

1. PassengerId - PassengerId.
2. Survival - Survival in Titanic.
3. pclass - Passenger class.
4. Name - Name of the passenger.
5. Sex - Sex.
6. Age - Age in year.
7. SibSp - Siblings/spouses aboard the Titanic.
8. Parch - Parents/children aboard the Titanic.
9. Ticket - ticket number.
10. Fare - Passenger fare.
11. Cabin - cabin number.
12. Embarked - Port of embarkation (C-Cherbourg, Q- Queenstown, S- Southampton, O- others)

# Section:

**Data Preprocessing and Cleaning**
1. Deals with NaN values using heatmap.
2. Drop the Cabin column.
3. Impute NaN Age based on the mean age.
4. Impute NaN Embarked based on the mode embarked.

**Data Visualization**
1. Plottig histogram of the dataset.
2. Illustrate the trends in survival rates and demographic characteristics.
3. Plotting passenger class survives.
4. Showing Distribution of Pclass Sex wise.

**Building Model**
1. Label encoding.
2. Selecting independent and dependent features.
3. Split data for training and testing.
4. Train,Predict, and evaluate the Logistic Regression, Random Forest Classifier, DecisionTreeClassifier,KNeighborsClassifier,SVC, and AdaBoostClassifier.
   


