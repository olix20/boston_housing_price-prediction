## Predicting Boston Housing Prices


The Boston housing market is highly competitive, and we want to be the best real estate agent in the area. We leverage a few basic machine learning concepts to assist us and a client with finding the best selling price for their home. 

The Boston Housing dataset  contains aggregated data on various features for houses in Greater Boston communities, including the median value of homes for each of those areas. We're going to build an optimal model based on a statistical analysis with the tools available. This model will then be used to estimate the best selling price for our client’s home.


A description of the dataset can be found [here](https://archive.ics.uci.edu/ml/datasets/Housing), which is provided by the **UCI Machine Learning Repository**.


### Install

This project requires **Python 2.7** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

I recommend installing [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project. 

### Code

The ipython notebook `boston_housing.ipynb` contains the code and our model building/verification process.  You can see it directly on github. If you'd like to run it, in a terminal or command window, navigate to the top-level project directory  (that contains this README) and run one of the following commands:

```ipython notebook boston_housing.ipynb```
```jupyter notebook boston_housing.ipynb```

This will open the iPython Notebook software and project file in your browser.

### Data

The dataset used in this project is included with the scikit-learn library ([`sklearn.datasets.load_boston`](http://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_boston.html#sklearn.datasets.load_boston)). You do not have to download it separately. You can find more information on this dataset from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Housing) page.
