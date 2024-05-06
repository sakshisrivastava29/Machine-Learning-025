# Machine-Learning-025



K-MEANS CLUSTERING :
It is a popular unsupervised machine learning algorithm used for partitioning data into clusters. The goal of K-means is to group similar data points together and discover underlying patterns in the data. Here's how it works:

Initialization: Start by choosing K initial centroids randomly from the data points. These centroids represent the centers of the clusters.
Assignment: Assign each data point to the nearest centroid, forming K clusters.
Update centroids: Recalculate the centroids of the clusters by taking the mean of all data points assigned to each cluster.
Repeat: Repeat steps 2 and 3 until the centroids no longer change significantly, or until a specified number of iterations is reached.
The algorithm aims to minimize the within-cluster variance, often measured by the sum of squared distances between data points and their respective centroids. K-means guarantees convergence to a local minimum, but the solution may vary depending on the initial centroids.


LINEAR REGRESSION :
It is a fundamental statistical technique used for modeling the relationship between a dependent variable (target) and one or more independent variables (predictors). It assumes a linear relationship between the predictor(s) and the target variable.Linear regression is commonly used for prediction, inference, and understanding the relationship between variables. It's important to assess the assumptions of linear regression, such as linearity, independence of errors, homoscedasticity (constant variance of errors), and normality of errors.


LOGISTIC REGRESSION :
It is a widely used statistical technique for binary classification problems, where the target variable has two possible outcomes (e.g., 0 or 1, yes or no, true or false).
The logistic regression model predicts the probability that a given input belongs to a particular class. It models the relationship between the dependent variable (binary) and one or more independent variables using the logistic function (also known as the sigmoid function).


MULTIPLE LINEAR REGRESSION :
It is used to estimate the relationship between two or more independent variables and one dependent variable. You can use multiple linear regression when you want to know:
How strong the relationship is between two or more independent variables and one dependent variable (e.g. how rainfall, temperature, and amount of fertilizer added affect crop growth).
The value of the dependent variable at a certain value of the independent variables (e.g. the expected yield of a crop at certain levels of rainfall, temperature, and fertilizer addition).


RANDOM FOREST:
It is a widely-used machine learning algorithm developed by Leo Breiman and Adele Cutler, which combines the output of multiple decision trees to reach a single result. Its ease of use and flexibility have fueled its adoption, as it handles both classification and regression problems.


SUPPORT VECTOR MACHINE:
SVM is a supervised machine learning algorithm used for both classification and regression. Though we say regression problems as well it’s best suited for classification. The main objective of the SVM algorithm is to find the optimal hyperplane in an N-dimensional space that can separate the data points in different classes in the feature space. The hyperplane tries that the margin between the closest points of different classes should be as maximum as possible. The dimension of the hyperplane depends upon the number of features. If the number of input features is two, then the hyperplane is just a line. If the number of input features is three, then the hyperplane becomes a 2-D plane. It becomes difficult to imagine when the number of features exceeds three. 
