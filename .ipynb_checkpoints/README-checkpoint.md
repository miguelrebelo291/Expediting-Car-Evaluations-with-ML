# Expediting-Car-Evaluations-with-ML
Group project developed for the Machine Learning course of the 2025/26 NOVA IMS Master’s in Data Science and Advanced Analytics.

## Notebook order
The project is built upon many notebooks that follow the following order:

    1. EDA.ipynb - Exploratory Data Analysis: General, univariate, and multivariate analysis. Preprocessing
    2. ModelSelection.ipynb - Model Evaluation and Selection: Pipeline construction, feature selection, modeling and evaluation, open-ended section.
    3. Deployment.ipynb - Model Deployment: Create submission for Kaggle competition

The remaining two notebooks are complementary to the ones mentioned before, yet still serve a purpose:

    a. HoldOut.ipynb - Holdout Method for Feature Selection: Complementary to notebook 2. Serves as a first insight for feature selection, before applying the cross-validation method.
    b. WebScraping_AutoTrader.ipynb - Web Scraping of Brand and Model Data Base: Complementary to notebook 1. Serves as an easier way of selecting the correct values for the "brand" and "model" features.

## Data files
As much of the data is collected through very time-consuming processes, the results obtained have been stored in CSV or Excel files. These are stored in different folders, and both folders and files are named according to the data stored in them. 