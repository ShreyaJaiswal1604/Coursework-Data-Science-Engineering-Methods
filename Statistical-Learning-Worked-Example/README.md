---


<h2><b>Predicting Life Expectancy and Health Insurance Linear Regression</h2></b>
<h3><b>Crash Course in Statistical Learning:Linear Regression Worked Examples<h3></b>
<hr>
 
<b>Shreya Jaiswal</b>

<hr>



<a href="https://githubtocolab.com/ShreyaJaiswal1604/Coursework-Data-Science-Engineering-Methods/blob/main/Statistical-Learning-Worked-Example/Predicting_Life_Expectancy_and_Health_Insurance_Linear_Regression.ipynb">
<img src="https://www.tensorflow.org/images/colab_logo_32px.png" />Run in Google Colab</a>
<hr>
<b>ABSTRACT</b>

<hr>
 
<ol>
<li>This study aimed to predict life expectancy and health insurance charges using linear regression on a dataset of demographic, lifestyle, and medical factors. The dataset contained information on over 1300 individuals and included features such as age, BMI, smoking status, region, and other health indicators</li>

<li>First, the data was preprocessed by removing missing values, encoding categorical variables, and scaling numerical features. Next, two separate linear regression models were trained to predict life expectancy and health insurance charges, respectively. The models were evaluated using metrics such as mean squared error, R-squared, and p-values to determine their accuracy and statistical significance</li>

<li>Overall, the findings suggest that linear regression can be an effective method for predicting life expectancy and health insurance charges based on demographic and health-related factors. The study has implications for healthcare policy and insurance pricing, as well as for individuals seeking to understand and manage their health risks</li>

<hr>
 

<h2><b>CONCLUSION</h2></b>
<hr>
 



*  Implemented Linear Regression for predicting Life Expectancy based on various factors such as the GDP of a country,  income composition of a country etc. Included preprocessing methods such as imputation and removing the outliers using methods such as winsorization methods.



* Linear Regression and other tree based models used to predict the life expectancy.

* Mathematically explained the algorithm and its statistical analysis.
 Defined the functions using the mathematical formula for MSE and VARIANCE and then compareD the obtained results from SCIKIT Built-in function.
 


*   In the Life Expectancy WHO dataset we have both numerical and categorical data

*   For this Linear Regression analysis we have taken one categorical column status as we are interested in wether the countries are Developed or Developing

*   The dataset consisted of null values for which Imputation methods have been performed and further analysis of the result has been made

*   The dataset also consists of Outliers which have been analysed using boxplot and appropriate methods have been performed to remove majority of the outliers

*   We also performed one hot encoding and various feature selection to otain the statistical measures such as the t-value, p-value

*   As the scale of the features were different, further normalization was performed on the dataset before btraining and testing the model.

*   Post normalization we split the dataset into training and testing and further compared both to make sure that the data across all the features are evenly distributed for the training and the testing dataset


*   We further obtained the statistical measures and obtained the MSE, Variance and percentage error etc.

*   In the Life Expectancy WHO dataset we have both numerical and categorical data

*   For this Linear Regression analysis we have taken one categorical column status as we are interested in wether the countries are Developed or Developing

*   The dataset consisted of null values for which Imputation methods have been performed and further analysis of the result has been made

*   The dataset has been analysed by H2O AutoML.

*   ThE models have been compared using H2O AutoML

*   Reports were generated using DataPrep Library.

*   Post normalization we split the dataset into training and testing and further compared both to make sure that the data across all the features are evenly distributed for the training and the testing dataset


*   We further obtained the statistical measures and obtained the MSE, Variance and percentage error etc.

*   In the Life Expectancy WHO dataset we have both numerical and categorical data

*   For this Linear Regression analysis we have taken one categorical column status as we are interested in wether the countries are Developed or Developing

*   The dataset consisted of null values for which Imputation methods have been performed and further analysis of the result has been made

*   Life Expectancy has been predicted using linear model.

*   Life Expectancy has been predicted using tree model.

*   Life Expectancy has been predicted using AutoML.

*   SHAP values have been used to compare and validate the model resullt


*   We further obtained the statistical measures and obtained the MSE, Variance and percentage error etc.




<hr>
 
**REFERENCES**

<hr>
 

*  Scikit learn Documentation
*  Plotly Documentation
*  Referred Analytics Vidhya Articles
*  Referred Towards Data Science Articles
* Referred Kaggle Notebooks
*  Topic specific references have been attached throughout the notebook for better understanding. The functions defined for ploting the residual graphs and finding the statistical measures has been written by me. 
*  It is very important to understand the concept and the terms before the impelentation of the same, Therefore I have defined the topic terms before their implementaion so that it would lead to a better understanding.

https://www.kdnuggets.com/2019/07/data-pre-processing-optimizing-regression-model-performance.html

https://quantifyinghealth.com/variables-to-include-in-regression/

https://towardsdatascience.com/understanding-the-ols-method-for-simple-linear-regression-e0a4e8f692cc

https://stackabuse.com/ultimate-guide-to-heatmaps-in-seaborn-with-python/

https://rpubs.com/sabrinapribadi/LinearRegression_LifeExpectancy

https://stats.stackexchange.com/questions/175/how-should-outliers-be-dealt-with-in-linear-regression-analysis

https://www.analyticsvidhya.com/blog/2021/09/q-q-plot-ensure-your-ml-model-is-based-on-the-right-distributions/

https://www.statsimprove.com/en/linear-regression-should-dependent-and-independent-variables-be-distributed-normally/

https://medium.com/swlh/exploratory-data-analysis-what-is-it-and-why-is-it-so-important-part-1-2-240d58a89695

https://towardsdatascience.com/linear-regression-explained-1b36f97b7572

https://www.analyticsvidhya.com/blog/2021/05/all-you-need-to-know-about-your-first-machine-learning-model-linear-regression/

https://corporatefinanceinstitute.com/resources/data-science/r-squared/

https://www.ncl.ac.uk/webtemplate/ask-assets/external/maths-resources/statistics/regression-and-correlation/residuals.html#:~:text=Definition,yi%E2%88%92%5Eyi.

https://www.khanacademy.org/math/statistics-probability/describing-relationships-quantitative-data/regression-library/a/introduction-to-residuals

https://www.analyticsvidhya.com/blog/2020/12/a-measure-of-bias-and-variance-an-experiment/

https://towardsdatascience.com/simple-mathematical-derivation-of-bias-variance-error-4ab223f28791


https://www.bmc.com/blogs/bias-variance-machine-learning/

https://medium.com/analytics-vidhya/calculation-of-bias-variance-in-python-8f96463c8942

https://study.com/learn/lesson/mean-squared-error-formula.html


https://vitalflux.com/ordinary-least-squares-method-concepts-examples/


https://towardsdatascience.com/understanding-the-ols-method-for-simple-linear-regression-e0a4e8f692cc

https://corporatefinanceinstitute.com/resources/data-science/r-squared/

https://www.analyticsvidhya.com/blog/2020/12/a-measure-of-bias-and-variance-an-experiment/

https://towardsdatascience.com/simple-mathematical-derivation-of-bias-variance-error-4ab223f28791


https://www.bmc.com/blogs/bias-variance-machine-learning/

https://medium.com/analytics-vidhya/calculation-of-bias-variance-in-python-8f96463c8942

---








---
---

### **Copyright**


---
---



> Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:



> The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.



>  THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
---





















































