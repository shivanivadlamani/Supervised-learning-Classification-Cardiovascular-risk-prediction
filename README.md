# Supervised-learning-Classification-Cardiovascular-risk-prediction
This repository contains code and data for a cardiovascular risk prediction project. The project uses a variety of machine learning models to predict the risk of cardiovascular disease in a population. The data used for the project is from the Framingham Heart Study, which is a long-term study of cardiovascular disease in the United States.


![image](https://github.com/shivanivadlamani/Supervised-learning-Classification-Cardiovascular-risk-prediction/assets/113968903/ea365c61-54a5-4743-8f58-f02d0517b3d5)


### here are the data points:

| Attribute            | Description                                                                 | Type     |
|----------------------|-----------------------------------------------------------------------------|----------|
| Sex                  | Male or female                                                              | Categorical |
| Age                  | Age of the patient                                                          | Continuous |
| Is Smoking           | Whether or not the patient is a current smoker                               | Categorical |
| Cigs Per Day         | The number of cigarettes that the person smoked on average in one day        | Continuous |
| BP Meds              | Whether or not the patient was on blood pressure medication                  | Categorical |
| Prevalent Stroke     | Whether or not the patient had previously had a stroke                       | Categorical |
| Prevalent Hyp        | Whether or not the patient was hypertensive                                  | Categorical |
| Diabetes             | Whether or not the patient had diabetes                                      | Categorical |
| Tot Chol             | Total cholesterol level                                                     | Continuous |
| Sys BP               | Systolic blood pressure                                                     | Continuous |
| Dia BP               | Diastolic blood pressure                                                    | Continuous |
| BMI                  | Body Mass Index                                                              | Continuous |
| Heart Rate           | Heart rate                                                                   | Continuous |
| Glucose              | Glucose level                                                                | Continuous |
| 10-year risk of CHD  | Binary: “1” means “Yes”, “0” means “No”                                      | Binary    |


The project was conducted in two phases. In the first phase, a variety of machine learning models were trained on the Framingham Heart Study data. The models were evaluated using a variety of metrics, including accuracy, precision, recall, and F1-score. The best performing model was a gradient boosting model, which had an accuracy of 0.834938.

In the second phase, the gradient boosting model was used to predict the risk of cardiovascular disease in a new population. The predictions were made using a variety of features, including age, sex, smoking status, blood pressure, cholesterol levels, and body mass index. The predictions were then compared to the actual cardiovascular disease status of the population. The results showed that the gradient boosting model was able to predict cardiovascular disease with a high degree of accuracy.

The code and data in this repository can be used to replicate the results of the project or to develop new cardiovascular risk prediction models. The code is written in Python and uses the scikit-learn machine learning library. The data is available in CSV format.
