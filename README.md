# Responsible Data Science 
# Final Project Proposal

## Description and Goal
For our final project, we examined an Automated Decision System (ADS) designed to predict whether a data scientist is likely to seek a new job, based on their activities and survey responses on a DS/AI learning platform. Using a variety of features, the ADS classifies each data scientist as either “job seeking” or “non-job seeking.” The system, published on [Kaggle](https://www.kaggle.com/code/joshuaswords/awesome-hr-data-visualization-prediction/notebook), includes data preprocessing, exploration, and model fitting through methods such as SVMs, decision trees, random forests, logistic regression, and KNN.

Our goal is to create a “nutritional label” for this ADS, evaluating potential biases in the data, processing steps, and the final machine learning classifications used to determine job-seeking status.

## Data
This [dataset](https://www.kaggle.com/code/joshuaswords/awesome-hr-data-visualization-prediction/notebook) was published by a Data Science learning platform looking to recruit data scientists who successfully completed specific certification courses. The algorithm is intended to identify factors that might influence a candidate to change jobs, both for targeted recruitment and to contribute to HR research on data scientist retention.

The model is trained on features representing each candidate’s credentials (e.g., education level, company type and size, training hours), demographics (e.g., gender, city), and work experience (e.g., years of relevant experience, years since last job). Many of these features are categorical, with some having high cardinality, and several contain missing data that required imputation.

The ADS output includes a probability prediction of whether a candidate may leave a job and an interpretation of the key factors influencing each individual’s decision.


## Motivation
We chose this dataset for several reasons. First, as data scientists entering the workforce, we’re interested in the dynamics of the job market within our field and the factors that influence job-seeking behavior among our peers. Understanding these factors not only gives us insight into our own career paths but also sheds light on trends in data science hiring and retention.

More importantly, this project allows us to examine critical issues of algorithmic fairness in hiring. Automated decision systems, especially those used in HR and hiring contexts, have significant influence on people’s employment opportunities. When biases exist—whether introduced through data imbalances, biased feature selection, or assumptions in preprocessing and modeling—these biases can perpetuate inequalities and potentially lead to unfair treatment of certain groups. In this dataset, demographic information such as gender and city could introduce potential disparities if the model performs differently across demographic subgroups.

Given the dataset’s imbalanced nature and reliance on categorical variables, as well as the need to make assumptions around missing values, this project provides a valuable opportunity to assess bias in data processing. We’ll evaluate both the technical biases within the prediction algorithm and its performance across demographic groups to assess whether it meets standards of group fairness. Ultimately, this project underscores the importance of responsible data science practices and the need for transparent, fair algorithms, especially in settings that impact individuals’ careers and livelihoods.


## Project Links and Resources
- Kaggle Description (https://www.kaggle.com/datasets/arashnic/hr-analytics-job-change-of-data-scientists)
- Data set & Notebook (https://www.kaggle.com/code/joshuaswords/awesome-hr-data-visualization-prediction/notebook)
