# Stanford Machine Learning Course by Andrew Ng
This repository holds my completed Octave/Matlab code for the exercises in the course. 


## Week 2 - Linear Regression with Multiple Variables (Exercise 1)
Files for building functions that:
- Explore data using scatter plots.
- Implement Gradient Descent using an appropriate Cost Function.
- Implement Gradient Descent using the closed-from normal equation.
- Normalise features to enhance Gradient Descent's convergence. 
- Use multivariate linear regression to make out-of-sample predictions.

![Scatter Plot](https://github.com/aabdelmak/Machine-Learning/blob/master/gradientcurve.png)


## Week 3 - Logistic Regression (Exercise 2) 
Files for building functions that:
- Implement Gradient Descent on an appropriate cost function. 
- Explore and discover appropriate weights with-which to regularise the Logistic Regression. 
- Implement a regularized version of Logistic Regression by using a modified cost function.  
- Deploy and use Logistic Regression to make out-of-sample predictions.

![Scatter Plot](https://github.com/aabdelmak/Machine-Learning/blob/master/logisticClassifier.png)


## Week 4 - Neural Networks: Representation (Exercise 3)
Files for building functions that:
- Build multi-class classifier composed of multiple linear regressions
- transform the data using a sigmoid link function to produce logistic regression
- Deploy the "One vs. All" method to classify handwritten digits and make out-of-sample classifications.
- Build a Feed-forward neural network with three layers.
- Train the neural network weights and biases on hand-written digits, storing the weights in a matrix
- Use the network to classify out-of-sample digits.

![Scatter Plot](https://github.com/aabdelmak/Machine-Learning/blob/master/mnistagain.png)


## Week 5 - Neural Networks: learning (Exercise 4)
- Implement a Feed-forward Neural Network using backprpagation from scratch to classify hand-written digits.
- Use Finite-Differences method for Gradient Checking.
- Enhance Neural Network performance and avoid over-fitting by implementing regularization.

![Scatter Plot](https://github.com/aabdelmak/Machine-Learning/blob/master/mnistviz.png)


## Week 6 - Advice for Applying Machine Learning (Exercise 5)
- Train a regularized linear regression to forecast water flow over a dam using various proportions of the training data.
- Plot the learning and validation curves to evaluate and debug the model's performance on the training and cross-validation sets.
- Compute and normalize polynomial features to experiment with polynomial regressions of various degrees, *d*, and use the cross-validation set to determine which value of *d* produces the optimal trade-off between bias and variance.
- Experiment with multiple regularization parameters, *lambda*, and plot the learning and validation curves to determine which value produces the optimal bias-variance trade-off.
- Compute and plot test-set error against cross-validation error to determine how well selected values of *lambda* and *d* generalize.  

![Scatter Plot](https://github.com/aabdelmak/Machine-Learning/blob/master/ex5graph.png)


## Week 7 - Advice for Applying Machine Learning (Exercise 6)
- Train a linear support vector machine (SVM) on a 2-dimensional example dataset to separate observations into two classes.
- Experiment with the effect of various values of the regularization term, C, to see how this affects classification accuracy.
- Train a support vector machine with radial-basis function kernel to classify 2-dimensional example dataset. 
- Test different regularization values, C, on cross-validation set to determine the optimal "softness" for classifier margins.
- Test different parameter values, sigma, for the rbf-kernel to determine optimal sensitivity of similarity metric to distance between observations.
- After preprocessing email data, create a feature vector with binary entries corresponding to whether each of the most frequently occurring words in our training set occurs in a given email.
- Further transform these features according to the rbf-kernel to acquire feature vectors that are to be used for training SVM.
- Train SVM to classify spam, testing different values of C and sigma on cross-validation set to determine their optimal values.

![Scatter Plot](https://github.com/aabdelmak/Machine-Learning/blob/master/svm2.png)

## Week 8 - Advice for Applying Machine Learning (Exercise 7)
- Implement the K-means algorithm for image compression by reducing the number of colors that occur in an image to only those that are most common in that image. 
- Use principal component analysis (PCA) to perform dimensionality reduction on a dataset of 5000 face images and visualize the result.
- Project 3-Dimensional data into a 2 Dimensionsional feature space using PCA implementation to make visualization less cumbersome. 

