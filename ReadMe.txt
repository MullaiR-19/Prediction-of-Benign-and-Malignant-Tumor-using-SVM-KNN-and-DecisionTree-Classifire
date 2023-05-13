##Prediction of Benign and Malignant Tumor using SVM, KNN and DecisionTree Classifier

In this project, we aim to predict the type of cancer (benign or malignant) using three different classifiers: SVM, KNN, and Decision Tree. 

*Since it is a binary classification problem, we have chosen SVM as our first choice classifier. We have used a poly kernel for SVM classification and achieved an accuracy of 94.4%. 
Also scaling is not required as there are no distance values between the columns. 

SVM Classifier is a supervised machine learning algorithm used for classification and regression analysis. 
It works by creating a hyperplane in n-dimensional space that maximally separates the different classes. 
In the context of cancer classification, SVM can be used to classify a given tumor as benign or malignant based on its features.

*Next, we have used KNN to classify the cancer type. We have used cross-validation to find the optimal value of n-neighbors, which turned out to be 8. 
Using this, we have achieved an accuracy of 93.7%. 

KNN Classifier is a simple, non-parametric algorithm used for classification and regression analysis.
It works by finding the k nearest neighbors of a given sample and then classifying it based on the majority class of those neighbors. 
In the context of cancer classification, KNN can be used to classify a given tumor as benign or malignant based on the similarity of its features to the features of the nearest neighbors.

*Finally, we have used the Decision Tree classifier to predict the cancer type. We have set the tree depth to 5 and achieved an accuracy of 92.3%.

Decision Tree Classifier is a tree-based algorithm used for classification and regression analysis.
It works by recursively splitting the data based on the features that provide the most information gain until a stopping criterion is met.
In the context of cancer classification, Decision Tree can be used to classify a given tumor as benign or malignant based on the features that provide the most information gain.

We have uploaded the code for this project to GitHub along with a detailed explanation of the methodology used, the dataset used, and the results obtained.

By making the code available on GitHub, other researchers and medical professionals can use and build upon our work to improve cancer type prediction and ultimately improve patient outcomes. 
