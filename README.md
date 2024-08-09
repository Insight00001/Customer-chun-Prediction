# Problem Statement
1. Develop a predictive model to identify customers at risk of churning
2. Analyze the key features leading to customer churnss

# Methods
1. Data Cleaning: Null values and duplicate values where removed
2. Exploratory Data Analysis: the dataset was visualized to gather hidden pattern and insights, the distribution of numerical features using histogram and catgorical features using countplot.

# Feature Engineering: 
1. feature creation: I created new features from existing ones
2. feature selection: I selected relevant features from the dataset
3. feature Encoding: Categorical features where converted to numerical values
5. feature scaling: the values where scaled using StandardScaler to reduce the margin between values
4. the data was split into train, test and validation
- the train set is feed into the machine learning model
- the validation set is used to validate the performance of the model
- test set is used to test the performance of the model to check how good the model can generalize on   new dataset

# Modelling
I used LogisticRegression(binary classification) and DecisiionTreeClassifier.

# Model Evaluation
## Linear Regression
Training Accuracy Score: 0.9723557692307693
Training Precision Score: 0.9751004016064257
Training Recall Score: 0.9696485623003195
Training f1_Score: 0.9723668402082499

Validation Accuracy Score: 0.968968968968969
Validation Precision Score: 0.9762845849802372
Validation Recall Score: 0.9629629629629629
Validation f1_Score: 0.9695780176643769

## Decision Tree

Training Accuracy Score: 0.9811698717948718
Training Precision Score: 0.979315831344471
Training Recall Score: 0.9832268370607029
Training f1_Score: 0.9812674372259865

Validation Accuracy Score: 0.9733066399733067
Validation Precision Score: 0.9733939000648929
Validation Recall Score: 0.9746588693957114
Validation f1_Score: 0.9740259740259741

## performance on test set
Logistic regression Accuracy Score: 0.9676680972818312
Logistic regression Precision Score: 0.9754831266224402
Logistic regression Recall Score: 0.9599772920806131
Logistic regression f1_Score: 0.9676680972818312

Decision tree Accuracy Score: 0.9701001430615165
Decision tree Precision Score: 0.9704713231118682
Decision tree Recall Score: 0.9701958558047119
Decision tree f1_Score: 0.970333569907736

the decision tree classifier performs better than the Logistic Regression model on the test set


# Conclusion
1. the most important features:
- the number of service interaction the customer had through email,chat,call
- the number of time the customer made late payment
- the time spent on the company's website
- the net promoter score(NPS)