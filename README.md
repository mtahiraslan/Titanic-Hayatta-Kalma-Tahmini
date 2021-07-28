On Jupyter Notebook with 'titanic.csv' dataset;

- Importing required libraries
- Uploading data
- Row and column information in the dataset
- Accessing statistical information in the data set
- Number of survivors
- Visualize the number of survivors
- Visualization of 'who','sex','pclass','sibsp','parch','embarked' columns in the dataset
- Calculation of survival rate by gender
- Visualization of survivors by gender and class
- Survival rate and visualization of each class
- Survival rates by age, class and gender
- Ticket price paid for each class and its visualization
- Values and their number in the data set
- Dropping columns we don't need and deleting columns with missing values
- Encoding of columns
- Splitting independent 'X' and dependent 'Y' variable from data information
- Reserve 80% of the dataset for train and 20% for testing
- Scaling of data
- Using Logistic Regression, k Neighbors, SVC Linear, SVC RBF, Gaussian Naive Bayes, Decision Tree and Random Forest models
- Recruitment and training of all models
- Finding the complexity matrix and Accuracy values of all models in the test data
- Feature and Importance visualization
- The model with the highest success rate is 'Random Forest Classifier' and these predictions are printed
- With the values I wrote, it was estimated whether I would survive with the Random Forest Model.

Columns in Data Set:
pclass: Passenger Class (1 = 1st class; 2 = 2nd class; 3 = 3rd class)<br>
survived: Survival (0 = No; 1 = Yes)<br>
name: Name<br>
sex: Gender<br>
age: age<br>
sibsp: Number of siblings/wives on board (eg: brother, sister, half-brother, half-sister)<br>
parch: Number of parents/children on board (eg: daughter, son, stepchild)<br>
fare: Passenger fare (British Pounds)<br>
embarked: Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)<br>
adult_male: A male over 18 years old? (0 = No, 1 = Yes)<br>
deck: Ship's deck<br>
who: man (18+), woman (18+), child (<18)<br>
alive: Yes, no<br>
embarked_town: Embarkation port ( Cherbourg, Queenstown, Southampton)<br>
class: Passenger classes (1st; 2nd; 3rd)<br>
alone:1=alone, 0=not alone (at least 1 sibling, spouse, parent or child on board)<br>
