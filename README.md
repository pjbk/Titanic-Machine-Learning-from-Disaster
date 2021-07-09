Titanic - Machine Learning from Disaster
⸺ The legendary Titanic ML competition in Kaggle


About

The sinking of the Titanic is one of the most infamous shipwrecks in history.

On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew. While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

In this challenge, it is asked to build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data. The dataset is available in [1].

Simply, use machine learning to create a model that predicts which passengers survived the Titanic shipwreck.

Dataset Description
Training set has 891 rows and test set has 418 rows,
Training set have 12 features and test set have 11 features. 
One extra feature in training set is Survived feature, which is the target variable.

PassengerId is the unique id of the row and it doesn't have any effect on target

Survived is the target variable we are trying to predict (0 or 1):
1 = Survived
0 = Not Survived

Pclass (Passenger Class) is the socio-economic status of the passenger and it is a categorical ordinal feature which has 3 unique values (1, 2 or 3):
1 = Upper Class
2 = Middle Class
3 = Lower Class

Name, Sex and Age are self-explanatory
SibSp is the total number of the passengers' siblings and spouse
Parch is the total number of the passengers' parents and children
Ticket is the ticket number of the passenger
Fare is the passenger fare
Cabin is the cabin number of the passenger

Embarked is port of embarkation and it is a categorical feature which has 3 unique values (C, Q or S):
C = Cherbourg
Q = Queenstown
S = Southampton

Proposed Approach: 
EDA, Data Preprocessing, Random Forest Classifier, Hyperparemeter tunung, Model Evaluation Metrics


***For more exciting notebooks visit my Kaggle workspace!***  [ https://www.kaggle.com/pankajbhowmik ]