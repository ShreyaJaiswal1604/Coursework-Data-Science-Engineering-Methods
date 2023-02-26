# Life Expectancy H20 AutoML


<a href="https://githubtocolab.com/ShreyaJaiswal1604/Coursework-Data-Science-Engineering-Methods/blob/main/AutoML/Life_Expectancy_H2O_AutoML.ipynb">
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
