# Life Expectancy H20 AutoML


<a href="https://githubtocolab.com/ShreyaJaiswal1604/Coursework-Data-Science-Engineering-Methods/blob/main/AutoML/Life_Expectancy_using_H2O_AutoML.ipynb">
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


---


### **CONCLUSION**

---


*   In the Life Expectancy WHO dataset we have both numerical and categorical data

*   For this Linear Regression analysis we have taken one categorical column status as we are interested in wether the countries are Developed or Developing

*   The dataset consisted of null values for which Imputation methods have been performed and further analysis of the result has been made

*   The dataset has been analysed by H2O AutoML.

*   ThE models have been compared using H2O AutoML

*   Reports were generated using DataPrep Library.

*   Post normalization we split the dataset into training and testing and further compared both to make sure that the data across all the features are evenly distributed for the training and the testing dataset


*   We further obtained the statistical measures and obtained the MSE, Variance and percentage error etc.





---
**REFERENCES**

---


*  Scikit learn Documentation
*  Plotly Documentation
*  Referred Analytics Vidhya Articles
*  Referred Towards Data Science Articles
* Referred Kaggle Notebooks

https://www.youtube.com/watch?v=WuuyD3Yr-js

https://www.youtube.com/watch?v=Q-TtIPF0fCU

https://www.youtube.com/watch?v=YE7E27-

Pycaret

https://www.youtube.com/watch?v=NbBoZQZ3bxo

https://www.youtube.com/watch?v=NbBoZQZ3bxo

https://www.youtube.com/watch?v=NbBoZQZ3bxo

https://www.kaggle.com/code/baotramduong/life-expectancy-prediction-with-h2o-automl/notebook

https://www.who.int/data/gho/data/themes/mortality-and-global-health-estimates/ghe-life-expectancy-and-healthy-life-expectancy

https://towardsdatascience.com/automated-machine-learning-with-h2o-258a2f3a203f

https://medium.com/mlearning-ai/life-expectancy-prediction-with-h2o-automl-91a36b4b06d2



*  Topic specific refernces have been attached throughout the notebook for better understanding. The functions defined for ploting the residual graphs and finding the statistical measures has been written by me. 
*  It is very important to understand the concept and the terms before the impelentation of the same, Therefore I have defined the topic terms before their implementaion so that it would lead to a better understanding.

---

**Copyright**


> Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:



> The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.



>  THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

































