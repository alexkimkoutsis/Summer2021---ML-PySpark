# Titanic Machine Learning Analysis
This is a machine learning analysis of the Titanic dataset.

The goal of the project was to correctly predict Titanic passenger survival based on their traits such as gender, age, and social class.

These analyses were performed in Jupyter notebooks and ran in two parts.

### Part 1 - titanic_data_analysis
Part 1 was an introduction to machine learning. This was my first time working with Jupyter notebooks, machine learning, pandas, scikit-learn, or even coding in Python.
As such, this was my first attempt at a complete data science / ML analysis.

In this part of the analysis, I conducted exploratory data analysis, cleaned the data, used scikit-learn to generate decision tree and random forest machine learning models, then attempted to tune the ML model hyperparameters to increase prediction accuracy.

### Part 2 - titanic_spark_analysis
Part 2 was my second go at conducting a data science analysis on this dataset. This time, I cleaned and explored the data more effectively.

Further, in this part I used Apache Spark (Pyspark) as my main tool for generating the machine learning models, as opposed to scikit-learn.

Lastly, in this part I utilized an explainability library called SHAP. Oftentimes, ML models are like black boxes. We input data, are returned results, but have no idea why the model made certain decisions. SHAP works to demystify ML modles by increasing their understandability. More details on SHAP are in the notebooks.

### Conclusions
Overall, I was able to get the accuracy of the machine learning models up to around 84%. While this is good, it could definitely be improved upon. In the future, I think that more extensive feature engineering could be used to significantly increase the ML prediction accuracy.

