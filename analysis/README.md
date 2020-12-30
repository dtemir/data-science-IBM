Data Analysis with Python is a **6 Weeks** course on the fundamentals of Explaratory Data Analysis.

| Week | Topic |Jupyter Notebook on Jupyter Nbviewer |
| ------ | ------ | ------ |
| 1 | Understanding the Data | [Notebook](https://nbviewer.jupyter.org/github/dtemir/data-science-IBM/blob/main/analysis/Understanding_Data.ipynb) |
| 2 | Wrangling the Data | [Notebook](https://nbviewer.jupyter.org/github/dtemir/data-science-IBM/blob/main/analysis/Wrangling_Data.ipynb) |
| 3 | Exploring the Data | [Notebook](https://nbviewer.jupyter.org/github/dtemir/data-science-IBM/blob/main/analysis/Exploring_Data.ipynb) |
| 4 | Model Development | [Notebook](https://nbviewer.jupyter.org/github/dtemir/data-science-IBM/blob/main/analysis/Model_Development.ipynb) |
| 5 | Model Evaluation | [Notebook](https://nbviewer.jupyter.org/github/dtemir/data-science-IBM/blob/main/analysis/Model_Evaluation.ipynb) |
| 6 | Final Assignment | [Notebook](https://nbviewer.jupyter.org/github/dtemir/data-science-IBM/blob/main/analysis/Final_Assignment.ipynb) |
* **Week 1** is about **understanding the data** on whether car prices depend on the attributes like Engine Type, Horsepower, MPG in Cities, or Milliage. To understand the data, we use *Pandas*, *NumPy*, *SciPy*, *Matplotlib*, *Seaborn*, and other libraries.
    * The Jupyter Notebook #1 is to explore the dataframe, the types of attributes, and other properties.
* **Week 2** is about **wrangling the data** to preprocess it for further analysis, such as turning categorical variables into quantitative, dealing with missing values, and normalizing values. 
    * The Jupyter Notebook #2 is to handle missing values by replacing them with their means or dropping them, correcting data format, standardizing data by converting columns, normalizing data with different approaches, and binning data into categories. 
* **Week 3** is about **exploring the data** with descriptive statistics, correlation and categorical association (Chi-Squary). 
    * The Jupyter Notebook #3 is to analyze individual feature patterns with visualization, exploring linear relationships between attributes, grouping data, building heat maps, and calculating correlation and ANOVA with *SciPy*.
* **Week 4** is about **model development** with linear regression, regression plots, pipelines, and measuring the perfomance.
    * The Jupyter Notebook #4 is to test three different prediction models through *Scikit-learn* (Simple Linear Regression, Multiple Linear Regression, and Polynomial Regression), build a pipeline, and test the models through their R-squared and MSE values.
* **Week 5** is about **model evaluation** with the concepts of overfitting, ridge regression, and grid search. 
    * The Jupyter Notebook #5 is to test the models with cross-validation score, check on overfitting with graphs, apply Ridge Regression, and find the best hyperparameters for the model with grid search
* **Week 6** is for the **final assignment**, analyze house prices based on features like the number of bedrooms, square feet, and the number of floors. We first import the data set, check the data types, and look at the <code>describe</code> property. We then wrangl the data, delete unneccesary columns and substitute NaNs with means of the columns. The third step is to do data analysis by building the graphs like boxplot and scatterplots on the features we think suit the model best. The fourth step is to develop a model, first with a simple Linear Regression, and then try other tecnhiques like a pipeline. The last step is to evaluate the model with cross validation, Ridge Reegression, and polynomial transformation for the training data.