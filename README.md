
# Employee Retention Prediction



## Objective

 1) To understand what factors contributed most to employee turnover.

2) To perform clustering to find any meaningful patterns of employee traits.

3) To create a model that predicts the likelihood if a certain employee will leave the company or not.

4) To create or improve different retention strategies on targeted employees.

5) The implementation of this model will allow management to create better decision-making actions.


## Dataset Used

The ‘HR Analytics’ data set , obtained from Kaggle
Website, This data set comprises ten attributes and 15000 tuples. 

Link : https://www.kaggle.com/jacksonchou/hr-analytics

Dataset features and the definitions of each one:
* satisfaction_level: Level of satisfaction {0–1}.
* last_evaluationTime: Time since last performance evaluation (in years).
* number_project: Number of projects completed while at work.
* average_montly_hours: Average monthly hours at workplace.
* time_spend_company: Number of years spent in the company.
* Work_accident: Whether the employee had a workplace accident.
* left: Whether the employee left the workplace or not {0, 1}.
*  promotion_last_5years: Whether the employee was promoted in the last five years.sales: Department the employee works for.
* salary: Relative level of salary {low, medium, high}.
## Tools and Technology

* Programing Language: Python
* Web Development Framework: Flask
* Machine Learning Libraries: Scikit-Learn, Pandas, Numpy, Matplotlib,seaborn, XGBoost
* Machine Learning Algorithm: KMeans, Random Forest and XGBoost
* Database: SQLite3
## Project development steps

Imported necessary libraries and dependencies and visualized different plots to understand more about data

• Checked correlation by viewing heatmap and pair plot to see multiple pairwise bivariate distributions

• Handled categorical data using statistical methods and separated the data into train and test

• Used grid search CV for hyper parameter tuning and exposed the data to Xgboost algorithm

• Created flask app and and exposed it as REST API to retrain and predict new set of data in future

• Created UI page to predict the result for single record from screen



## Run Locally

Clone the project

```bash
  git clone https://github.com/Siddhantshelake/Employee-Retention-Prediction.git
```

Go to the project directory

```bash
  cd Employee-Retention-Prediction
```

Install requirements

```bash
  pip install requirements.txt
```

Start the application 

```bash
   run main.py 
```


## Screenshots

 ### Not Retained
![App Screenshot](https://github.com/Siddhantshelake/Employee-Retention-Prediction/blob/master/screenshots/not%20retained.PNG)

### Retained

![App Screenshot](https://github.com/Siddhantshelake/Employee-Retention-Prediction/blob/master/screenshots/retain.PNG)
## Demo

![alt-text](https://github.com/Siddhantshelake/Employee-Retention-Prediction/blob/master/ERP.gif)

