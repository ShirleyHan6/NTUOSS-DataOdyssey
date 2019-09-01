# NTUOSS-DataOdyssey
**By [Han Simeng](https://github.com/ShirleyHan6) from [NTU Open Source Society](https://www.ntuoss.com)**

<!-- blank line -->
![alt text](https://github.com/ShirleyHan6/NTUOSS-DataOdyssey/blob/master/images/logo.jpeg)
Artwork by Brendan Hyde

---
<!-- blank line -->


| Workshop Details |                                                                                       |
| :---:            | ---                                                                                   |
| When             | Friday, 9 Sep 2018. 6:30 PM - 8:30 PM                                                |
| Where            | LT1, NTU North Spine Plaza                                                            |
| Who              | NTU Open Source Society                                                               |
| Questions        | We will be hosting a Pigeon Hole Live for collecting questions regarding the workshop |
### Errors

For errors, typos or suggestions, please do not hesitate to [post an issue](https://github.com/wilsonteng97/NTUOSS-PandasBasics/issues/new)! Pull requests are very welcome, thank you!

**_Disclaimer: This workshop is for educational purposes only. No prototype or outcome of any type is intended for commercial use._**

---
### Introduction

Data science is highly regarded as one of the most important skills to learn. But what is data science even about, and how do you utilize it? For the next three weeks, NTU Open Source Society will be hosting 3 workshops designed to introduce the concept from a novice level to how companies use data science in the real world.<br>
![alt text](https://github.com/ShirleyHan6/NTUOSS-DataOdyssey/blob/master/images/scikit_learn.png)
The second workshop will introduce two machine learning algorithms in order to demonstrate how the field can be used in real-world scenarios. <br>
This includes logistic regression, a supervised method to solve classification problems, as well as k-means clustering, an unsupervised method to group together clusters of data by certain criteria.<br>
We will use [scikit-learn](https://scikit-learn.org/stable/index.html), a python package built for implement machine learning algorithms. <br>
[Logistic Regression with scikit-learn](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html)<br>
[K-Means with scikit-learn](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html)<br>

### Google Colabtory
See [NTUOSS-PandasBasics](https://github.com/wilsonteng97/NTUOSS-PandasBasics) for a comprehensive introduction on how to use Google Colabtory for data science projects and let's walk through it. <br>

### Odyssey Begins
![title](images/ml_types.jpg)
1. [Supervised Odyssey: `Supervised Classification`](#supervised)
    * [Packing up: Environment Setup](#prep)
    * [Data Exploration](#explore1)
    * [Data Classification: `Logistic Regression`](#logreg)
      + [Intuition](#intuition1)
      + [Coding with sklearn](#coding1)
    * [Result Visualization](#viz1)
2. [Unsupervised Odyssey: `Unsupervised Classification`](#unsupervised)
    * [Data Exploration](#explore1)
    * [Image Compression: `K-Means`](#k_means)
      + [Intuition](#intuition2)
      + [Coding with sklearn](#coding2)
    * [Result Visualization](#viz2)
3. [End of journey](#end)

##  Supervised Odyssey: Supervised Classification <a name="supervised"></a>
###  Packing up: Environment Setup <a name="prep"></a>
> Install machine learning and visualization packages
<!-- blank line -->
![alt text](https://github.com/ShirleyHan6/NTUOSS-DataOdyssey/blob/master/images/code/environment_setup/install_package.png)
<!-- blank line -->
> Import the module for linear regression algorithm from sklearn and plotting packages
<!-- blank line -->
![alt text](https://github.com/ShirleyHan6/NTUOSS-DataOdyssey/blob/master/images/code/environment_setup/import_libs.png)
<!-- blank line -->
### Data Exploration
> Use numpy to load the file as a data object
![alt text](https://github.com/ShirleyHan6/NTUOSS-DataOdyssey/blob/master/images/code/supervised/load_data.png)
> Inspect more details
![alt text](https://github.com/ShirleyHan6/NTUOSS-DataOdyssey/blob/master/images/code/supervised/more_details.png)
> Plot all data
![alt text](https://github.com/ShirleyHan6/NTUOSS-DataOdyssey/blob/master/images/code/supervised/plot.png)
![alt text](https://github.com/ShirleyHan6/NTUOSS-DataOdyssey/blob/master/images/code/viz/explore1.png)
## Data Classification: Logistic Regression <a name="logreg"></a>
### Algorithm Intuition ([online demo](https://www.desmos.com/calculator/naf1qogfjn))<a name="intuition1"></a>
![alt text](https://github.com/ShirleyHan6/NTUOSS-DataOdyssey/blob/master/images/logreg.png)
### Coding with sklearn <a name="coding1"></a>
> The sigmoid value of X, which is computed by the f_pred function, is the value of y predicted by the model. 
![alt text](https://github.com/ShirleyHan6/NTUOSS-DataOdyssey/blob/master/images/code/supervised/log_reg1.png)
## Logistic regression/classification predictive function 
![alt text](https://github.com/ShirleyHan6/NTUOSS-DataOdyssey/blob/master/images/code/supervised/log_reg_eqn.png)
> Make a LogisticRegression object <br>
> Fit the data to the model <br>
> Get the parameters for plotting the data, W_0, W_1 and W_2 <br>
![alt text](https://github.com/ShirleyHan6/NTUOSS-DataOdyssey/blob/master/images/code/supervised/log_reg2.png)
> After obtaining the parameters, lets visualize the result by plotting the decision boundary. <br>
Students whose score points are above the decision boundary will be admitted while the students below the decision boundary will be rejected
![alt text](https://github.com/ShirleyHan6/NTUOSS-DataOdyssey/blob/master/images/code/supervised/viz1.png)
> Now let's use our trained logistic regression model to predict if a student will be accepted or rejected.
![alt text](https://github.com/ShirleyHan6/NTUOSS-DataOdyssey/blob/master/images/code/supervised/predict1.png)
## Unsupervided Odyssey: Unsupervised Classification <a name="unsupervised"></a>
> Install Pillow, which is used with matplotlib to read images in jpep format
![alt text](https://github.com/ShirleyHan6/NTUOSS-DataOdyssey/blob/master/images/code/unsupervised/install_libs2.png)
> Import the image reading module from matplotlib and the K-Means module from sklearn
![alt text](https://github.com/ShirleyHan6/NTUOSS-DataOdyssey/blob/master/images/code/unsupervised/import_libs2.png)
## Data Exploration <a name="explore2"></a>
# Read the image
![alt text](https://github.com/ShirleyHan6/NTUOSS-DataOdyssey/blob/master/images/code/unsupervised/read_reshape_img.png)
## Image Compression: K-Means <a name="k_means"></a>
### Algorithm Intuition ([Online Demo](http://alekseynp.com/viz/k-means.html))<a name="intuition2"></a>
![alt text](https://github.com/ShirleyHan6/NTUOSS-DataOdyssey/blob/master/images/k_means.png)
### Coding with sklearn <a name="coding2"></a>
> Reshape the image to be 2-dimension, then run the KMeans algorithm with the number of clusters equal to 20. 
>Fit the model to the data, then use the centroids to compress the image
![alt text](https://github.com/ShirleyHan6/NTUOSS-DataOdyssey/blob/master/images/code/unsupervised/k_means_cluster.png)
## Data Visualization <a name="viz2"></a>
> Reshape X_recovered to have the same dimension as the original image<br>
> Now we can plot the original and the compressed image side by side. 
![alt text](https://github.com/ShirleyHan6/NTUOSS-DataOdyssey/blob/master/images/code/unsupervised/viz2.png)
## End of Odyssey!<a name="end"></a>
![alt text](https://github.com/ShirleyHan6/NTUOSS-DataOdyssey/blob/master/images/ai_ml_dl.png)


