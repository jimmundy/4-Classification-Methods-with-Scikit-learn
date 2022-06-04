### <a id="intro"></a> 1. INTRODUCTION

##### **OBJECTIVE**: Explore Scikit-learn with 4 machine learning CLASSIFICATION methods by employing two different evaluation metrics **`Jaccard score`** and **` F1 score`**.

#### What is Scikit Learn?
Scikit-learn is an open-source machine learning library for the Python programming language. It implements a good number of algorithms for tasks such as classification, clustering and regression. Sci-kit learn also provides so many utilities for carrying out machine learning tasks. With Scikit Learn, we can carry out data processing, parameter selection, model evaluation, and more.

The objective here is to introduce how to implement Scikit-learn for machine learning using a specific dataset. Most of the models and algorithms in the Scikit-Learn library are treated in approximately the same approach: basically, we
1. Call a **`fit`** to train the intended model
2. Check the accuracy of the model with a call, **`score`**
3. Forecast the model's outcome (or predict the model) by using **`predict`**.


*Let's go*:

####  Dataset
The dataset (in CSV format) is about past loans and includes details of 400 customers whose loans are either `paid off` or `defaulted`. In machine learning and statistics, **`classification`** is a supervised learning approach in which the computer program learns from some input data and then uses this learning to classify new observations.

We load the dataset using the `Pandas` library and then apply the 4 classification algorithms: 'K Nearest Neighbor(KNN)', 'Decision Trees', 'Support Vector Machine' and 'Logistic Regression', and then find the best algorithm by carrying out some accuracy evaluation methods.

Below is a  quick **summary of the column data features**:

| Category       | Description                                                                           |
| :---           | :----                                                                                 |
| Loan_status    | Loan is 'paid off' on in 'collection'                                                 |
| Principal      | Basic principal loan amount                                                           |
| Terms          | Origination terms: weekly (7 days), biweekly, monthly payoff schedule                 |
| Effective_date | Loan originated and effective date                                                    |
| Due_date       | Since it’s one-time payoff schedule, each loan has one single due date                |
| Age            | Age of applicant                                                                      |
| Education      | Education of applicant                                                                |
| Gender         | Gender of applicant                                                                   |





