## [Project 1: Red Wine Quality: Project Overview](https://github.com/sykes14596/Red_Wine_Quality)

* Created a model that predicts the quality rating of red wine with 85% accuracy.
* Target variable redefined into a binary classification due to unbalanced classes.
* SMOTE technique implemented to create perfectly balanced classes to allow for the solving of the original problem.
* Reduced multicolinearity issues by removing redundant variables.
* Implemented a range of different models, including Logistic Regression and XGBoost classifiers.

![](/Images/Correlation_Matrix.png)

## [Project 2: Student Exam Scores: Project Overview](https://github.com/sykes14596/Student_Exam_Results)

For years, students have been using their predicted grades in an effort to monitor their progress throughout their chosen subjects. More recently, as a result of the Covid-19 pandemic, predicted grades have been used by exam boards, particularly within the UK, as a student's final grade. As a result, the accurate prediction of these grades has grown significantly more important.

* Created models to solve 3 different problems based on the definition of the target variables.
* Identified possible outlying data points and investigated the potential reasons behind these points.
* In the multiclass classification problem, SMOTE technique implmented to create perfectly balanced target classes.
* Range of different model types implemented to gain programming experience using them.

![](/Images/test_scores_pairplot.png)

## [Project 3: Used Car Prices: Project Overview](https://github.com/sykes14596/Used_Car_Prices)

The goal of this project was to be able to accurately predict the sale price of a range of used cars, as well as to practice skills and techniques learned through the completion of Jose Portilla's "Python for Data Science Bootcamp" on Udemy.

A wide range of models were implemented and the effect of scaling data was investigated. The most accurate model, based on its Root Mean Squared Error (RMSE), was a Random Forest Regressor trained and tested on the scaled version of the dataset. The model achieved an R2 score of 96.4% and a RMSE of £1858.

* Dealt with erroneous data points across each of the independent variables.
* Appied a logarithmic transform of numerical features to reduce skewness.
* Range of model types built to practice producing the code required to implement them. 
* Chose 2 different metrics for analysing model performance.
* Scaling data seemed to affect model performance in varying ways depending on the model used.

![](/Images/manufacturer_boxplot.png)

## [Project 4: Breast Cancer Prediction: Project Overview](https://github.com/sykes14596/Breast_Cancer_Prediciton)

The goal of this project was to develop a model that would accurately predict the presence of breast cancer within a patient. On a personal development level, the aim of this project was to practice the skill known as feature selection, as well as continue to use and develop data analysis skills learned via completion of Jose Portilla's "Python for Data Science Bootcamp" course on Udemy.

* Feature selection used by creating feature importance dataframes and creating models with different numbers of input features.
* F1-score used to determine which number of features was optimal.
* SMOTE technique implemented to produce balanced classes.
* Random Forest and XGBoost Classifiers used to produce 99% accuracy on the test set.

![](/Images/RFC_SMOTE_plot.png)
