# Census-Income-Prediction

The above introduction had an aim to increase the awareness about how the income factor actually has an impact not only on the personal lives of people, but also an impact on the nation and its betterment. We will today have a look on the data extracted from the 1994 Census bureau database, and try to find insights about how different features have an impact on the income of an individual. Though the data is quite old, and the insights drawn cannot be directly used for derivation in the modern world, but it would surely help us to analyze what role different features play in predicting the income of an individual.


The dataset provided to us contains 32561 rows, and 14 different independent features. We aim to predict if a person earns more than 50k$ per year or not. Since the data predicts 2 values (>50K or <=50K), this clearly is a classification problem, and we will train the classification models to predict the desired outputs.

Data Dictionary : 
1. Age — The age of an individual, this ranges from 17 to 90.
2. Workclass — The class of work to which an individual belongs.
3. Fnlwgt — The weight assigned to the combination of features (an estimate of how many people belong to this set of combination)
4. Education — Highest level of education
5. Education_num — Number of years for which education was taken
6. Marital_Status — Represents the category assigned on the basis of marriage status of a person
7. Occupation — Profession of a person
8. Relationship — Relation of the person in his family
9. Race — Origin background of a person
10. Sex — Gender of a person
11. Capital_gain — Capital gained by a person
12. Capital_loss — Loss of capital for a person
13. Hours_per_week — Number of hours for which an individual works per week
14. Native_Country — Country to which a person belongs
15. Income — The target variable, which predicts if the income is higher or lower than 50K$.
