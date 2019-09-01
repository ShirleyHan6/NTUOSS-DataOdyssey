# NTUOSS-DataOdyssey
<!-- blank line -->
![alt text](https://github.com/ShirleyHan6/NTUOSS-DataOdyssey/blob/master/images/logo.jpeg)
<!-- blank line -->

Repository for workshop on Practical Machine Learning. <br>
This is the second workshop of NTUOSS Data Science Workshop Series for AY19/20
_by [Han Simeng](https://github.com/ShirleyHan6) for [NTU Open Source Society](https://github.com/ntuoss)_

### Workshop Details

**When**: Friday, 6 September 2019. 6:30 PM - 8:30 PM.</br>
**Where**: LT1 Nanyang Technological University</br>
**Who**: NTU Open Source Society

### Questions

Please raise your hand any time during the workshop or email your questions to [me](mailto:hans0035@e.ntu.edu.sg) later.

### Errors

For errors, typos or suggestions, please do not hesitate to [post an issue](https://github.com/wilsonteng97/NTUOSS-PandasBasics/issues/new)! Pull requests are very welcome, thank you!

---
### Introduction

Data science is highly regarded as one of the most important skills to learn. But what is data science even about, and how do you utilize it? For the next three weeks, NTU Open Source Society will be hosting 3 workshops designed to introduce the concept from a novice level to how companies use data science in the real world.<br>

The second workshop will introduce two machine learning algorithms in order to demonstrate how the field can be used in real-world scenarios. <br>
This includes logistic regression, a supervised method to solve classification problems, as well as k-means clustering, an unsupervised method to group together clusters of data by certain criteria.<br>
We will use [scikit-learn](https://scikit-learn.org/stable/index.html), a python package built for implement machine learning algorithms. <br>
[Logistic Regression with scikit-learn](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html)<br>
[K-Means with scikit-learn](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html)<br>

### Google Colabtory
See [NTUOSS-PandasBasics](https://github.com/wilsonteng97/NTUOSS-PandasBasics)for a comprehensive introduction on how to use Google Colabtory for data science projects and let's walk through it. <br>

### Odyssey Begins
![title](images/ml_types.jpg)
1. [Supervised Odyssey: Supervised Classification](#supervised)
    * [Packing up: Environment Setup](#prep)
    * [Data Exploration](#explore1)
    * [Data Classification: Logistic Regression](#logreg)
      + [Intuition](#intuition1)
      + [Coding with sklearn](#coding1)
    * [Result Visualization](#viz1)
2. [Unsupervised Odyssey: Unsupervised Classification](#unsupervised)
    * [Data Exploration](#explore1)
    * [Image Compression: K-Means](#k_means)
      + [Intuition](#intuition2)
      + [Coding with sklearn](#coding2)
    * [Result Visualization](#viz2)
3. [End of journey](#end)

##  Supervised Odyssey: Supervised Classification <a name="supervised"></a>
###  Packing up: Environment Setup <a name="prep"></a>
Install machine learning and visualization packages
<!-- blank line -->
![alt text](https://github.com/ShirleyHan6/NTUOSS-DataOdyssey/blob/master/images/code/environment_setup/install_package.png)
<!-- blank line -->
Import the module for linear regression algorithm from sklearn and plotting packages
<!-- blank line -->
![alt text](https://github.com/ShirleyHan6/NTUOSS-DataOdyssey/blob/master/images/code/environment_setup/import_libs.png)
<!-- blank line -->

### Data Exploration
Use numpy to load the file as a data object
![alt text](https://github.com/ShirleyHan6/NTUOSS-DataOdyssey/blob/master/images/code/supervised/load_data.png)
Inspect more details
![alt text]()
Plot all data
![alt text]()
## Data Classification: Logistic Regression <a name="logreg"></a>
### Algorithm Intuition ([online demo](https://www.desmos.com/calculator/naf1qogfjn))<a name="intuition1"></a>
![alt text]()
### Coding with sklearn <a name="coding1"></a>
The sigmoid value of X, which is computed by the f_pred function, is the value of y predicted by the model. 
![alt text]()
## Logistic regression/classification predictive function 
![alt text]()
![alt text]()
![alt text]()
![alt text]()
![alt text]()
![alt text]()
![alt text]()
![alt text]()
![alt text]()
![alt text]()
![alt text]()
![alt text]()
![alt text]()
![alt text]()
![alt text]()
![alt text]()