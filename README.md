A series of Quarto markdown files (.qmd) are stored in this repository for an updated version of this old post on
"Small molecules in ChEMBL database - Series 1.1 - Polars dataframe library and machine learning in scikit-learn". This old post will be updated and splitted into four smaller posts for the ease of reading (and also to avoid draining my energy too quickly). 

A quick overview on what each post will be about:

1st post - storing the small molecules data from ChEMBL in a compressed parquet file format using Polars dataframe library as the original .csv file is about 660 MB for ChEMBL version 31

2nd post - preprocessing the data using Polars dataframe library prior to building a machine learning model 

3rd post - building a logistic regression model using scikit-learn and Polars dataframe library

4th post - evaluations of the logistic regression model using various calculations or metrics in scikit-learn

Each post also has its own Jupyter notebook version saved in the folder named "Jupyter_notebooks". Current ETA for posting is roughly towards the end of October or in November (I may try posting one post each week or something along that line).