# Cryptocurrencies
Python/Pandas, Jupyter Notebook, scikit-learn packages (sklearn.preprocessing, sklearn.decomposition, sklearn.cluster), Plotly

[Resource used to drop 'Unnamed:0' column from initial DataFrame read-in](https://net-informations.com/ds/err/unnamed.htm)

[Resource used to pull index from another DataFrame](https://stackoverflow.com/questions/18176933/create-an-empty-data-frame-with-index-from-another-data-frame)

[Resource used to concatenate two DataFrames together](https://www.geeksforgeeks.org/how-to-combine-two-dataframe-in-python-pandas/)

[Resource used to join a column from one DataFrame to another](https://www.geeksforgeeks.org/how-to-add-column-from-another-dataframe-in-pandas/)

## Overview of Cryptocurrencies

#### The purpose of this repository/challenge is to group a dataset on cryptocurrencies using an unsupervised machine learning model utilizing clustering. The idea is to simulate grouping these cryptocurrencies to create a classification system to demystify them. As you can see from the visualizations of the full analysis, it still looks a bit messy. 

![1](https://i.gyazo.com/1a9fd6b50de13bdc51eb849de94294fc.png)
![2](https://i.gyazo.com/200257da06f3f503fbf6bd3e52a423f8.png)

#### Regardless of the results, the data was preprocessed for PCA (Principal Component Analysis), then PCA was used to reduce the dimensions of the data and assign it its class. According to this [BuiltIn.com article](https://builtin.com/data-science/step-step-explanation-principal-component-analysis), PCA is defined as:
>a dimensionality reduction method that is often used to reduce the dimensionality of large data sets

#### After that, the data was clustered by class using the K-Means algorithm, and then visualized into the 3D model and scatter plot seen above using hvPlot.

#### I personally wouldn't say that the classification of the data is clean, concise, or readable, but it is classified. Whether this is an issue of the dataset or the unpredictable nature of cryptocurrency is up to personal interpretation, but I bet on the latter. All summary given above can also be supplemented followed through the included "crypto_clustering.ipynb" Jupyter Notebook file. 
