# Machine Learning Linear Regression and Time Series Forecasting
# Machine Learning
# Feature Engineering
Feature engineering is the process of selecting, manipulating, and transforming raw data into features that can be used for creating a predictive model using Machine learning or statistical Modelling.
### One-hot Encoding
-	One-hot encoding is a process of converting categorical data variables so they can be provided to machine learning algorithms to improve predictions.
-	The Python library Pandas provides a function called __get_dummies__ to enable one-hot encoding
### map() function
-	To convert numerical data variables can use the map() function
### Scaling
Feature scaling is about transforming the values of different numerical features to fall within a similar range like each other. The feature scaling is used to prevent the supervised learning models from getting biased toward a specific range of values.
-	StandardScaler for Standardization
    - StandardScaler is a class from sklearn.preprocessing which is used for standardization.
    - Standardization is used to center the feature columns at mean 0 with a standard deviation of 1 so that the feature columns have the same parameters as a standard normal distribution.

-	MinMaxScaler for Normalization
    - MinMaxScaler is a class from sklearn.preprocessing which is used for normalization.
    - Normalization refers to the rescaling of the features to a range of [0, 1], which is a special case of min-max scaling.
    
# Preprocessing Modeling
Preprocessing is the most important aspect of data processing. When data is acquired as an output of an experiment, the next step is modeling the data to extract useful information.
###	Feature Selection
Feature selection is the process of selecting the features that contribute the most to the prediction variable or output that you are interested in, either automatically or manually.
###	Feature Importance
Feature importance assigns a score to each of your data’s features; the higher the score, the more important or relevant the feature is to your output variable.
- Extra Trees Classifier
     - Extra Trees Classifier is a type of ensemble learning technique which aggregates the results of multiple de-correlated decision trees collected in a “forest” to output it’s classification result.
###	Train Test Split
- The train-test split is a technique for evaluating the performance of a machine learning algorithm.
# Modeling
In this topic, the modeling that will be explained is Simple Linear Regression, Multiple Linear Regression, and Time Series.

**Step 1**: Fitting into training

**Step 2**: Predic the result

**Step 3**: Plot the result

## Multiple Linear Regression 
- Multiple linear regression is a statistical method to estimate the relationship between two or more independent variables and one dependent variable.
# Evaluate Model
-	One way to evaluate models is to use MAPE
-	The Mean Absolute Percentage Error (MAPE) can be used in machine learning to measure the accuracy of a model.
-	Interpretasion of MAPE
    -	*> 50%		: The accuracy of model is **Poor**
    -	20% - 50%	: The accuracy of model is **Relatively good**
    -	10% – 20%	: The accuracy of model is **Good**
    -	< 10%		  : The accuracy of model is **Great**
