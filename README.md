# Best-Classifier

### About Project
Multiple classification algorithms were used and the best one for this specific datset was found through accuracy evaluation methods.


### About dataset
This dataset is about past loans. The Loan_train.csv data set includes details of 346 customers whose loan are already paid off or defaulted. It includes following fields:


| Field          | Description                                                                           |
| -------------- | ------------------------------------------------------------------------------------- |
| Loan_status    | Whether a loan is paid off on in collection                                           |
| Principal      | Basic principal loan amount at the                                                    |
| Terms          | Origination terms which can be weekly (7 days), biweekly, and monthly payoff schedule |
| Effective_date | When the loan got originated and took effects                                         |
| Due_date       | Since it’s one-time payoff schedule, each loan has one single due date                |
| Age            | Age of applicant                                                                      |
| Education      | Education of applicant                                                                |
| Gender         | The gender of applicant                                                               |

### Libraries Used
- Itertools
- Numpy
- Pandas
- Matplotlib
- Seaborn
- Scikit Learn
- Urllib

### Algorithms Used
- K Nearest Neighbour (KNN)
- Decision Tree
- Support Vector Machine
- Logistic Regression

### Result
| Algorithm          | Jaccard | F1-score | LogLoss |
| ------------------ | ------- | -------- | ------- |
| KNN                | 0.72    | 0.84     | NA      |
| Decision Tree      | 0.71    | 0.83     | NA      |
| SVM                | 0.70    | 0.83     | NA      |
| LogisticRegression | 0.75    | 0.86     | 0.48    |
