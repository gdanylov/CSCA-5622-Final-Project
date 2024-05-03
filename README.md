# Decision Tree Classifier for Titanic Dataset
## Objective
The accident that occurred on the Titanic is one of the most infamous shipwrecks of all time. On April 15, 1912, the Titanic collided with an iceberg, killing 1502 out of 2224 people on board. A large reason this was such a tragic accident was because there were not enough lifeboats to accommodate all the passengers on the boat. 
This resulted in some people getting chosen to get on a lifeboat and some people were not chosen. This was a difficult decision, and certain characteristics such as sex, age, and class played a factor in the outcome of the passenger’s survival.
The objective of this project was to build a model to predict whether or not a passenger survived the Titanic.


## Data Description
Variables and Definitions:
1. Survival - Did the passenger survive? 0 = No, 1 = Yes
2. Pclass - Ticket class; 1 = First, 2 = Second, 3 = Third
3. Sex - Sex of passenger
4. Age - Age of passenger in years
5. Sibsp - # of siblings/spouses aboard the Titanic
6. Parch - # of parents/children aboard the Titanic
7. Ticket - Ticket number
8. Fare - Passenger Fare
9. Cabin - Cabin Number
10. Embarked - Port of embarkation; C = Cherbourg, Q - Queenstown, S = Southampton

### Variable Notes
**Pclass** can be used to determine the socio-economic status of the passenger
Feature engineering was used to create new variables such as Family Size that can provide more value than Sibsp and Parch.
Furthermore, from the Family Size it is easier to see whether or not the passenger travelled alone, and whether or not it affect the survival rate of the passenger.

## Files used
train.csv

## Benefits of Decision Tree Classifier
1. Decision tree classifiers are easy to understand and interpret. This is useful for understanding the logic behind the predictions.
