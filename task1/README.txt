Objective:

Here, I worked on cleaning and preparing raw data for machine learning. The objective was to deal with missing values, transform categorical data into numbers, scale numerical features, and clean out any outliers — all the necessary steps before feeding data into a model.

Tools Used: 

Python for scripting
Pandas & NumPy for data handling
Seaborn / Matplotlib for visualizations
scikit-learn for preprocessing techniques

Dataset:

Dataset: Titanic – Machine Learning from Disaster
Source: Kaggle Titanic Competition
(You can also use a local copy if downloaded manually)

What I Did (Step-by-Step):

1. Loaded & Explored the Data
Checked out the structure of the dataset using .info() and .describe()
Identified columns with missing data and types that needed converting

2. Cleaned Missing Values
Replaced missing values in the Age column with the median (less sensitive to outliers)
Filled missing Fare values with the mean
Dropped a couple rows where the Embarked field was not present (just a few)

3. Encoded Categorical Features
Applied one-hot encoding for the Sex and Embarked features
This converts them into binary features, which are simpler for ML models to process

4. Standardized Numerical Features
Used StandardScaler to scale the Age and Fare features
This assists models in converging quicker and avoids large numbers from overpowering

5. Detected & Removed Outliers
Plot boxplots for Fare and Age to identify outliers
Applied the IQR method of removing extreme values from the dataset

Visualisations: 
To enhance the understanding of the data, I produced:
Boxplots of Fare and Age to identify outliers
Before-and-after plots illustrating the impact of cleaning

Outcome:
At the end of this activity, the dataset was cleaner, balanced, and ready for machine learning model use. All these preprocessing activities greatly enhance model performance and accuracy.
