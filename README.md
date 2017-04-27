# Market Intelligence Using Unsupervised Learning

In this repository, we will demonstrate how to perform market intelligence by analyzing a dataset containing annual spending amounts on a range of consumables of a given market for internal structure.  We apply [Principal Components Analysis (PCA)](https://en.wikipedia.org/wiki/Principal_component_analysis) to understand underlying variation in the customers, and use a [Gaussian Mixture Model](https://en.wikipedia.org/wiki/Mixture_model#Gaussian_mixture_model) to segment the market accordingly.  Actionable items based on market intelligence are discussed.

_Examples of GMM clusters:_
![alt text](http://i.imgur.com/YXTifBk.jpg)

# Goals

We demonstrate an unsupervised learning method for classifying agents into segments based on their behavior, using retail purchasing of consumables as an example.  Heavy emphasis is placed on analysis and inference.

## Software and Library Requirements
* Python 2.7.11
* Jupyter Notebook 4.2.2
* Numpy 1.11.2
* scikit-image 0.12.3
* matplotlib 1.5.2

## Data

The sample data used for this notebook comes from the [UCI Irvine Machine Learning repository](https://archive.ics.uci.edu/ml/datasets/Wholesale+customers).

Each agent in the market has the following attributes:

1)	FRESH: annual spending (m.u.) on fresh products (Continuous); 
2)	MILK: annual spending (m.u.) on milk products (Continuous); 
3)	GROCERY: annual spending (m.u.)on grocery products (Continuous); 
4)	FROZEN: annual spending (m.u.)on frozen products (Continuous) 
5)	DETERGENTS_PAPER: annual spending (m.u.) on detergents and paper products (Continuous) 
6)	DELICATESSEN: annual spending (m.u.)on and delicatessen products (Continuous); 

## Getting up and running

While in the `market_intelligence` directory, use the following command in your command line interface:

> `ipython notebook market_intelligence_walktrhrough.ipynb`
