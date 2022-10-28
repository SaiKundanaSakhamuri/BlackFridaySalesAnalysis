# Machine-Learning-Project-Starter
Repository of all project documentation and Code

My previous selected project was *Breast Cancer Detection using Monogram*. I realized the loopholes in that and the problems I will face going forward.
- the analysis is to be extracted from an image
- The selected dataset doesn�t help me explore more ML concepts going further.
- most of the datasets have missing values
- it covers only regression from our course work

## My new project : **Black Friday Sales Prediction**.


### PROBLEM STATEMENT
Predicting customer behavior from previous sales help in targeting and reaching estimated sales in various fields like finance, sales, marketing. This analysis helps us in predicting the purchase amount of customer against various products. Which in turn helps in creating offers for a particular range of customers. For instance, if we take the electronics category, past sales reveal there are a more customers under the age group of 40. So, applying offers in that specific range of age groups helps in the sales market and they can come up with new offers that can attract customers from other age ranges.<br>
Machine Learning analytics helps us achieve this. By building such predictive models, we can predict the impact of the decisions taken on the growth of our organization.<br>
In this project, we are going to predict how much the customers will spend during Black Friday, using various features such as age, gender, marital status. For this we will be using different machine learning algorithms like Linear Regression, Decision Tree, Random Forest. <br>
### FEATURES
| Column ID |         Column Name        | Data type |           Description           | Masked |
|:---------:|:--------------------------:|:---------:|:-------------------------------:|--------|
|     0     |           User_ID          |   int64   |      Unique Id of customer      | False  |
|     1     |         Product_ID         |   object  |       Unique Id of product      | False  |
|     2     |           Gender           |   object  |         Sex of customer         | False  |
|     3     |             Age            |   object  |         Age of customer         | False  |
|     4     |         Occupation         |   int64   |   Occupation code of customer   | True   |
|     5     |        City_Category       |   object  |         City of customer        | True   |
|     6     | Stay_In_Current_City_Years |   object  | Number of years of stay in city | False  |
|     7     |       Marital_Status       |   int64   |    Marital status of customer   | False  |
|     8     |     Product_Category_1     |   int64   |       Category of product       | True   |
|     9     |     Product_Category_2     |  float64  |       Category of product       | True   |
|     10    |     Product_Category_3     |  float64  |       Category of product       | True   |
|     11    |          Purchase          |   int64   |         Purchase amount         | False  |

### COMBINATION OF FEATURES
No. In comparison to combining the features with those that already exist, the features taken into consideration above will produce better results.<br>
### OUTPUT/ANSWER
The above taken features will help us derive different kinds of prediction purchase amount.<br>
By evaluating the relation between different other features and purchase amount we can provide more prediction analysis.<br>
### DATASET
[Primary dataset](https://www.kaggle.com/datasets/kkartik93/black-friday-sales-prediction) <br>
[Supporter dataset](https://www.kaggle.com/code/sourabhgumtaj/black-friday-eda-sourabh-gumtaj/data)<br>
As there are ample features to support the predictions, primary dataset is efficient enough for our project. But going further for any other references the supporter dataset can be used.<br>
### Libraries

<li>pandas
<li>matplotlib
<li>seaborn
<li>scikit-learn

### Algorithms used until now

<li>Linear Regression
    
### Files and Content
| File Name                           |         Content                                                                                                        |
|:-----------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| BlackFridaySales.csv                | Consists of the data sets, exported from the Primary dataset link provided above                                       |
| BlackFridaySalesPrediction_Proposal |           A word document defines the problem statement and explains the analysis approach of this project             |
| initial_exploration.ipynb           | Retreived dataset from the csv file. Analyzed, cleaned and created traing and test data sets                           |
|  linear_regression.ipynb            | Preapared the dataset for Linear regression.Declared the initial set of features for X and the target feature y.Tried 3                                                 different approaches for linear regression.Discussed the results after each approach of Linear Regression.           |
