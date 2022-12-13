## Predicting Heart Disease

The [World Health Organization (WHO)](https://www.who.int/health-topics/cardiovascular-diseases) estimates that 17.9 million people die from cardiovascular diseases (CVDs) every year. There are multiple risk factors that could contribute to CVD in an individual, such as unhealthy diet, lack of physical activity, or mental illness. Identifying these risk factors early on could help prevent many premature deaths.

Here we work with an anoymized [dataset](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction) that includes relevant information for each patient, such as their personal information and some medical data, including whether or not they have had heart disease before. We are tasked with using the dataset to accurately predict the likelihood of a new patient having heart disease in the future.

### Contents:
- Exploratory Data Analysis
- Data Cleaning
- Feature Selection
- Building a Classifier

### Summary: 
After performing an exploratory data analysis and cleaning of the the data, features were selected using a logistic regression model with L1 regularization. These features were subsequently used with a KNN classifier to develop a model that achieved **~84% accuracy for predicting heart disease**. 

### Potential Improvements:
- The datasets have a significantly higher number of male patients than female ones. This imbalance could present a bias in our dataset and it potentially impacts our model. 
- Another similar issue is age. This could be another factor that influences the model and could be explored.
- Only enlisted a single algorithm as used. An ensemble of algorithms could help to find the algorithm that serves as the best classifer.