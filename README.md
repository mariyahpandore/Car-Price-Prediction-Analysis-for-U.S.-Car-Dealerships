# Car-Price-Prediction-Analysis-for-U.S.-Car-Dealerships
To aid car dealers in better measuring the value of cars, this project utilized machine learning algorithms to construct statistical models to explore the influence of car features on price, and the best model to estimate car price.


* [1. Introduction](#Introduction)
    * [1.1 Used Packages](#Used-Packages)
    * [1.2 Import Dataset](#Import-Dataset)
* [2. Data Exploration](#Data-Exploration)
    * [2.1 Dataset Overview](#Dataset-Overview)
    * [2.2 Identify the Problems in the Dataset](#Identify-the-Problems-in-the-Dataset)
        * [2.2.1 Find the Dulicated Values](#Find-the-Dulicated-Values)
        * [2.2.2 Find the Missing Values](#Find-the-Missing-Values)
        * [2.2.3 Figure out Specific Problems in Columns](#Figure-out-Specific-Problems-in-Columns)
* [3. Data Preparing](#Data-Preparing)
    * [3.1 Data Cleaning](#Data-Cleaning)
        * [3.1.1 Dealing with Duplicate Values, Improper Datatype and Missing Values](#Dealing-with-Duplicate-Values,-Improper-Datatype-and-Missing-Values)
        * [3.1.2 Dealing with Outliers](#Dealing-with-Outliers)
            * [Dropping Price Outliers](#Dropping-Price-Outliers)
            * [Dropping Mileage outliers](#Dropping-Mileage-outliers)
            * [Dropping Levy Outliers](#Dropping-Levy-Outliers)
    * [3.2 Facts about the Dataset](#Facts-about-the-Dataset)
        * [3.2.1 Summary Statistics](#Summary-Statistics)
        * [3.2.2 Data Visulization](#Data-Visulization)
        * [3.3 Feature Selection](#Feature-Selection)
            * [3.3.1 Correlation Analysis: Choosing the Most Important Numerical Variables](#Correlation-Analysis:-Choosing-the-Most-Important-Numerical-Variables)
            * [3.4.2 Box Plot Analysis: Choosing the Most Important Categorical Variables](#Box-Plot-Analysis:-Choosing-the-Most-Important-Categorical-Variables)
            * [3.4.3 Feature Engineering](#Feature-Engineering)
            * [3.4.4 Feature Scaling](#Feature-Scaling)
* [4. Model Training](#Model-Training)
    * [4.1 Dataset Splitting](#Dataset-Splitting)
    * [4.2 Multiple Linear Regression](#Multiple-Linear-Regression)
        * [The Most Significant Variables for the Model](#The-Most-Significant-Variables-for-the-Model)
        * [Error Analysis](#Error-Analysis)
    * [4.3 Decision Tree Regressor](#Decision-Tree-Regressor)
        * [The Most Significant Variables for the Model](#The-Most-Significant-Variables-for-the-Model)
        * [Error Analysis](#Error-Analysis)
    * [4.4 Random Forest Regressor](#Random-Forest-Regressor)
        * [The Most Significant Variables for the Model](#The-Most-Significant-Variables-for-the-Model)
        * [Error Analysis](#Error-Analysis)
    * [4.5 Model Evalution](#Model-Evalution)
        * [Measure and Compare Model Performance](#Measure-and-Compare-Model-Performance)
        * [Error Analysis](#Error-Analysis)
        * [Shortlisting the Most Promising Model](#Shortlisting-the-Most-Promising-Model)
        * [Hyper Parameter Adjustment](#Hyper-Parameter-Adjustment)
* [5. Conclusion and Recommendation](#Conclusion-and-Recommendation)
* [6. Reference](#Reference)


**Data Exploration**

The dataset used in this project contains information on various car features such as number of airbags, production year, mileage, and more. The first step in the project was to explore the dataset and identify any problems in the data such as duplicated values and missing values. The data was then cleaned and prepared for the next step.

**Data Preparation**

After exploring the dataset, the next step was to clean and prepare the data. This involved dealing with duplicate values, improper data types, and missing values, as well as dealing with outliers in the data. The data was then analyzed to understand its features and characteristics through summary statistics and data visualization. The most important numerical and categorical variables were then selected through correlation analysis and box plot analysis.

**Model Training**

The next step was to train the models on the prepared dataset. The dataset was split into training and testing sets, and three different models were used: multiple linear regression, decision tree regressor, and random forest regressor. The most significant variables for each model were identified, and the performance of the models was measured and compared through R-squared and error analysis.

**Model Evaluation**

The performance of the models was evaluated by measuring their R-squared value, which is a measure of how well the model fits the data. The R-squared values for the multiple linear regression, decision tree and random forest models were 39%, 60%, and 73% respectively. This indicates that the random forest regressor was the most accurate model in predicting car prices.

**Conclusion and Recommendation**

This project has explored various factors to predict the price of cars in order to guide car dealerships to set a price that will maximize demand, increase their margins, and ultimately maximize their profit. The recommendation is to use the random forest regressor model when predicting car prices and focus on the three most relevant car features: number of airbags, production year, and mileage.
