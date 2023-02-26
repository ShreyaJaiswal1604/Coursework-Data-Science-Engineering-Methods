# Life Expectancy H20 AutoML


<a href="https://githubtocolab.com/ShreyaJaiswal1604/Coursework-Data-Science-Engineering-Methods/blob/main/AutoML/Life_Expectancy_H2O_AutoML.ipynb">
<img src="https://www.tensorflow.org/images/colab_logo_32px.png" />Run in Google Colab</a>


<hr>
<h3> ABSTRACT</h3>

> **Automated Machine Learning (AutoML)** is the process of automating tasks in the machine learning pipeline such as 
> 1.   data preprocessing
> 2.   hyperparameter tuning
> 3. model selection and evaluation

> H2O AutoML trains and cross validates the following models:
> <ol>
> <li>Three pre-specified XGBoost GBM (Gradient Boosting Machine) models</li>
> <li>Fixed grid of GLMs (Generalized Linear Model)
> <li>Default Random Forest (DRF)
> <li>5 pre-specified H2O GBMs
> <li>Near-default Deep Neural Net
> <li>Extremely Randomized Forest (XRT)
> <li>Random grid of XGBoost GBMs
> <li>Random grid of H2O GBMs
> <li>Random grid of Deep Neural Nets
> <li>Multiple Stacked Ensemble models will also be trained throughout the process
> </ol>

<hr>
<h3> PROJECT OVERVIEW</h3>
  

---



> The project aims to predict Life-Expectancy on the WHO dataset and analyse models on different models generated using AutoML H2O.



> The following process has been implemented in the project
1.   **ABOUT THE DATASET**
      1. Life Expectancy

> 2.  **LIFE EXPECTANCY PREDICTION WITH H2O AUTOML**

> 3. **PROBLEM STATEMENT**

> 4. **WHAT IS AutoML?**

> 5. **IMPORTANT METRICS**

> 6. **FUNCTIONS**


> 7. **READ THE DATA**

> 8. **CLEANING THE DATA COLUMNS NAMES**


>9. **EXPLORATORY DATA ANALYSIS (EDA)**
      1. Analysing Median Life Expectancy over the years
      


>10. **DATA PREPROCESSING**
      1. NULL VALUE ANALYSIS
      2. IMPUTATION
      3. Performing Imputation by filling the null values of the feature with the corresponding median obtained over the years
      4. PERFORMING ONE-HOT ENCODING ON THE CATEGORICAL DATA COLUMN : STATUS
>11. **DATA VISUALIZATION WITH DATAPREP**
>12. **MODEL EVALUATION**
>13. **MODEL EXPLAINABILITY IN AUTOML H2O**
 1. Residual Analysis for Leader Model
  2. Variable Importance of Top Base (non-Stacked) Model
 3. Variable Importance Heatmap (compare all non-Stacked models)
 4. Model Correlation Heatmap (compare all models)
 5.SHAP Summary of Top Tree-based Model (TreeSHAP)
 6. Partial Dependence (PD) Multi Plots (compare all models)
 7.Individual Conditional Expectation (ICE) Plots
 
 >14.**CONCLUSION**
 
 >15.**REFERENCES**
 
 >16.**Copyright**



---

























