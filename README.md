# Shipping-inspection-classifier
A coursework project I created, on shipments being inspected by customs

## What does it show?

The notebook shows three models I made and evaluated against one another, all attempting to predict whether a given shipment handled at a port would be inspected by customs or not. The three models I chose were:
1. Support Vector Machine (SVM)
2. SVM with stochastic gradient descent
3. Bagging classifier, with decision tree as the base estimator

## Why did I make this?

I needed to complete a piece of coursework on classifier models; the dataset I found presented some interesting challenges like:
* Missing data or other data quality issues
* Low correlations between the feature and target variables
* Non-numerical data (requiring decisions on how best to encode)
* High-dimensionality data after aforementioned encoding
