# **Capstone Project**:
The capstone project was conducted to showcase the skills developed through a professional Machine Learning and Artificial Intelligence program. The project utilized the Cross-Industry Standard Process for Data Mining (CRISP-DM) methodology, which involves six phases: Business Understanding, Data Understanding, Data Preparation, Modeling, Evaluation, and Deployment. The project aimed to answer a question of interest using various tools and techniques encountered during the program.

**CRISP-DM FARMWORK**:

**Business Understanding**: 
The challenge for home buyers is the exorbitant house prices which prevent many people from buying their dream home. Instead of describing the physical features of their ideal home, people often begin with concerns about price negotiations. Many people are unable to afford their dream home due to the increasing cost of houses, leading them to live in rental properties. This situation is often exploited by real estate agents who charge high rent prices.

Goal: The project aims to compare regression models and select the best one that can predict an affordable sale price for residential home buyers in Ames, Iowa. The models will be trained on original feature data and log-transformed target, and the results will be compared to recommend the best model.

**Data Understanding**:

**About Dataset**:

Data Source: https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview

The data for the project was obtained from Kaggle, a popular platform for data science and machine learning. The dataset contains 81 explanatory variables that describe different aspects of residential homes in Ames, Iowa. The data understanding phase of the project involved assessing data availability, collection, granularity, and quality, as well as exploring the data.

 **Data Preparation**:
The data preparation step involves organizing the data into a structured form, resolving structure errors, removing and correcting incorrect, corrupt, and duplicated data. This is a time-consuming  and heavy lifting task and accounts for almost 80% of the project. Removing outliers is also a part of data preparation that helps to improve model performance.

The project only kept features that have below 10% missing values, as the features with more than 10% missing values, are not helpful for the data exploratory analysis and are discared.

**Modeling**

The Modeling phase is the phase in which machine learning models are trained and tested to select the best model that can solve the business problem. This phase involves the training of various regression models, ensemble regressors, and deep neural networks.

The final capstone project involved training and testing several regression models, including Linear Regression, Ridge Regression, RandomForestRegressor, AdaBoostRegressor, GradientBoostRegressor, and Depp Neural Network.

Feature engineering was performed on the data to select, extract, and transform the relevant features. This was done because the performance of a machine learning model depends heavily on the quality and relevance of the features used.

After feature engineering, the data was split into training and testing sets using the train-test-split tool from the scikit learn package. The training set was used to train the machine learning model to learn patterns in the data and make predictions, while the testing set was used to evaluate the performance of the model on unseen data.
A linear method 

Principal Component Analysis (PCA) was used to transform high-dimensional data into a lower-dimensional representation. This involved a linear transformation that seeks to find the directions of maximum variance in the data. PCA was chosen for this task because it is computationally efficient, can handle large datasets effectively, and is faster than other methods of dimensionality reduction.

**Note**: The application of PCA resulted in the extraction of 42 components that explained more than 90% of the variance in the data. However, due to limitations in the processing unit of the computer, only 10 of these components were considered for further analysis.








