# Decision Tree Classifier for Titanic Dataset
## Objective
Create a model that can predict which passengers survived on the Titanic.

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
