README for G08 
--------------

Project title: Signal Detection in M-PSK Modulation Under Channel’s Additive Noise and False Data Injection

This project contains 4 MAIN FILES as follows: 

#1: Dataset_Generation_G08.ipynb
This notebook file shows how the dataset is created.
 
#2: Main_File_G08.ipynb
This notebook file contains the main codes of the project and includes the following subsections:

- importing the dataset
- plotting dataset
==================================================================================================
- training SVM classifier based on K-fold cross-validation and grid search (without PCA)
	* report the achieved results on the training set and test set
	* plotting confusion matrix 
==================================================================================================
- training MLP classifier based on K-fold cross-validation and grid search (without PCA)
	* report the achieved results on the training set and test set
	* plotting confusion matrix 
==================================================================================================
- training Logistic Regression classifier based on K-fold cross-validation and grid search (without PCA)
	* report the achieved results on the training set and test set
	* plotting confusion matrix 
==================================================================================================
- Define encoding scheme based on PCA
	* Explained variance graph
	* plotting features before and after applying PCA
==================================================================================================
- training SVM classifier based on K-fold cross-validation and grid search (using PCA for different number of components)
	* report the achieved results on the training set and test set
	* plotting confusion matrix 
==================================================================================================
- training Logistic Regression classifier based on K-fold cross-validation and grid search (using PCA for different number of components)
	* report the achieved results on the training set and test set
	* plotting confusion matrix 
==================================================================================================
- training MLP classifier based on K-fold cross-validation and grid search (using PCA for different number of components)
	* report the achieved results on the training set and test set
	* plotting confusion matrix 
==================================================================================================
- Anomaly Detection
	* Define 5 anomalous samples and add them to the normal dataset
	* Define normal label as 0 and anomalous label = 1
	* Visualization of normal samples and anomalous samples
	* Fit a multivariate Gaussian distribution to the normal samples
	* Choosing ϵ (threshold) based on try and error approach
	* Define a function to choose the best  ϵ  based on f1-score
	* Visualization of the achieved results 
==================================================================================================
#3: X.npy
Contain the samples and features of the dataset that has been used in the project.

#4: y.npy
Contain the labels of the dataset that has been used in the project. 
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
NOTE: to run the notebook files, all files should be in the same folder. 