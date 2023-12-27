<<<<<<< HEAD
<<<<<<< HEAD
# Life Expectancy Regression ML


<a href="https://githubtocolab.com/ShreyaJaiswal1604/Coursework-Data-Science-Engineering-Methods/blob/main/ML%20Data%20Cleaning%20and%20Feature%20Selection/Life_Expectancy_Regression_ML.ipynb">
<img src="https://www.tensorflow.org/images/colab_logo_32px.png" />Run in Google Colab</a>
<hr>
<h3> ABSTRACT</h3>

A Linear Regression Model has been designed to find the Life Expectancy based on factors such as adult mortality, schooling, health state of different countries categorised as developed or developing. Life Expectancy in today's world depends on various factors and is extremely important in determining human developments in every field. This project aims to perform the basic analysis on the WHO dataset to understand the basic concept behind ML Data Cleaning and Feature Selection.
<hr>
<h3> PROJECT OVERVIEW</h3>
The project aims to perform Exploratory Data Analysis (EDA) on the WHO dataset and implement linear regression model to predict the Life Expectancy.

The following process has been implemented in the project

<OL>
<li>ABOUT THE DATASET</li
<li>Life Expectancy</li>
<li>IMPORT LIBRARIES</li>
<li>READ THE DATA</li>
<li>CLEANING THE DATA COLUMNS NAMES</li>
<li>EXPLORATORY DATA ANALYSIS (EDA)</li>
<UL>
<li>Distribution of Life Expectancy</li>
<li>Correlation Heatmap for dependency Visualization</li>
<li>HeatMap</li>
<li>Correlation Matrix</li>
<li>Plotting Life Expectance vs Adult Mortality for developed and developing countries</li>
<li>Plotting Life Expectance vs GDP for developed and developing countries</li>
<li>Plotting Life Expectance vs Schooling using hex plot</li>
<li>Plotting Life Expectance vs income composition of resources for developed and developing countries using KDE plot</li>
</UL>
<li>DATA PREPROCESSING</li>
<li>DATA PREPROCESSING</li>
<li>IMPUTATION</li>
<UL>
<li>Performing Imputation by filling the null values of the feature with the corresponding median obtained over the years</li>
<li>HANDLING OUTLIERS</li>
<li>ENCODING THE CATEGORICAL DATA</li>
</UL>
<li>FEATURE ENGINEERING</li>
<li>Q-Q PLOT</li>
<li>HISTOGRAM PLOT</li>
<li>PERFORMING NORMALIZATION USING ROBUSTSCALAR</li>
<li>IDENTIFYING PREDICTOR SIGNIFICANCE OR FEATURE SELECTION</li>
</UL>
<li>BUILDING THE MODEL</li>
<UL>
<li>Train,Test Split</li>
<li>Comparing trainig data and testing data</li>
<li>Linear Regression model</li>
<li>Predicting with test data</li>
<li>Evaluating the model using metric</li>
</UL>
<li>UNDERSTANDING THE IMPORTANT FEATURES</li>
<li>PERMUTATION MODEL</li>
<li>Answer the following questions:</li>
</OL>
<hr>
<h3> DATASET OVERVIEW</h3>

<ol>
Life Expectancy is the statistical measure of the average time a person is expected to live based on a variety of factors such as age, sex, health, demographic factors etc.

The WHO Dataset consists 2938 rows and 22 columns

The columns are as followed

<li>COUNTRY : Country name</li>
<li>YEAR: Year ranges from 2000 - 2015</li>
<li>LIFE EXPECTANCY : Life Expectancy in age</li>
<li>ADULT MORTALITY : Probability of dying between 15-60 years per 1000 population</li>
<li>INFANT DEATHS : Number of infant deaths per 1000 population</li>
<li>ALCOHOL : Recorded per capita consumption in litres</li>
<li>PERCENTAGE : Recorded as percentage of Gross Product per capita(%)</li>
<li>HEPATITIS B: Immunization coverage among 1 year old</li>
<li>MEASLES : Number of cases reported per 1000 population in percentage (%)</li>
<li>BMI : Average Body Mass Index of the population</li>
<li>UNDER-FIVE-DEATHS: Number of under five deaths per 1000 population</li>
<li>POLIO : Immunization coverage among 1 year old in percentage (%)</li>
<li>TOTAL EXPENDITURE : Government expenditure on heath as a percentage of total government expenditure</li>
<li>DIPTHERIA : DPT Immunization among the 1 year old in percentage (%)</li>
<li>HIV/AIDS : Deaths per 1000 live births</li>
<li>POPULATION : Population of the country</li>
<li>THINNESS 1-19 YEARS: Prevalence of thinness among children and adolescents for Age 10 to 19 (%)</li>
<li>INCOME COMPOSITION OF RESOURCES: Human Development Index based on income and availability of resources. Ranges between 0 and 1</li>
<li>THINNESS 5-9 YEARS : Prevalence of thinness among children and adolescents for Age 5 to 9 (%)</li>
<li>SCHOOLING : Number of years of Schooling in years</li>
<li>GDP : Gross Domestic Product per vcapita ( in USD)</li>
<li>STATUS : Developed or Developing Country</li>
</ol>
<hr>
<h3> CONCLUSION </h3>
<ul>
<li>In the Life Expectancy WHO dataset we have both numerical and categorical data</li>
<li>For this Linear Regression analysis we have taken one categorical column status as we are interested in wether the countries are Developed or Developing</li>
<li>The dataset consisted of null values for which Imputation methods have been performed and further analysis of the result has been made</li>
<li>The dataset also consists of Outliers which have been analysed using boxplot and appropriate methods have been performed to remove majority of the outliers</li>
<li>We also performed one hot encoding and various feature selection to otain the statistical measures such as the t-value, p-value</li>
<li>As the scale of the features were different, further normalization was performed on the dataset before btraining and testing the model.</li>
<li>Post normalization we split the dataset into training and testing and further compared both to make sure that the data across all the features are evenly distributed for the training and the testing dataset</li>
<li>We further obtained the statistical measures and obtained the MSE, Variance and percentage error etc.</li>

<hr>
<h3> REFERENCES </h3>
<hr>
<ul>
<li>Scikit learn Documentation</li>
<li>Plotly Documentation</li>
<li>Referred Analytics Vidhya Articles</li>
<li>Referred Towards Data Science Articles</li>
<li>Referred Kaggle Notebooks</li>
<li>https://www.youtube.com/playlist?list=PLIo0T9rfFycRG2Ninz7QlDB7jKbat8xfZ</li>

<hr>
<li>https://quantifyinghealth.com/variables-to-include-in-regression/</li>
<li>https://towardsdatascience.com/understanding-the-ols-method-for-simple-linear-regression-e0a4e8f692cc</li>
<li>https://stackabuse.com/ultimate-guide-to-heatmaps-in-seaborn-with-python/</li>
<li>https://rpubs.com/sabrinapribadi/LinearRegression_LifeExpectancy</li>
<li>https://stats.stackexchange.com/questions/175/how-should-outliers-be-dealt-with-in-linear-regression-analysis</li>
<li>https://www.analyticsvidhya.com/blog/2021/09/q-q-plot-ensure-your-ml-model-is-based-on-the-right-distributions/</li>
<li>https://www.statsimprove.com/en/linear-regression-should-dependent-and-independent-variables-be-distributed-normally/</li>
<li>https://medium.com/swlh/exploratory-data-analysis-what-is-it-and-why-is-it-so-important-part-1-2-240d58a89695</li>
</ul>
<hr>
=======
=======
>>>>>>> 89018f072d97fe8a5536d80b3b3dd750eb2288ad
# Life Expectancy H20 AutoML


<a href="https://githubtocolab.com/ShreyaJaiswal1604/Coursework-Data-Science-Engineering-Methods/blob/main/AutoML/Life_Expectancy_Using_H2O_AutoML%20.ipynb">
<img src="https://www.tensorflow.org/images/colab_logo_32px.png" />Run AutoML H20 in Google Colab</a>



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

































<<<<<<< HEAD
>>>>>>> 89018f072d97fe8a5536d80b3b3dd750eb2288ad
=======
>>>>>>> 89018f072d97fe8a5536d80b3b3dd750eb2288ad
