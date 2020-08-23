# PCA references and links:

https://www.youtube.com/watch?v=GyyrnOHwe2E

https://www.youtube.com/watch?v=4KuF5HRAQn8&t=983s

https://medium.com/analytics-vidhya/a-beginners-guide-for-dimensionality-reduction-using-principle-component-analysis-pca-c4c515ae49c1

https://wiki.pathmind.com/eigenvector

http://colah.github.io/posts/2014-10-Visualizing-MNIST/

https://www.appliedaicourse.com/lecture/11/applied-machine-learning-online-course/2906/questions-answers/2/module-2-data-science-exploratory-data-analysis-and-data-visualization

https://github.com/ranasingh-gkp/PCA-TSNE-on-MNIST-dataset/blob/master/14_15_16(PCA%2CT_SNE).ipynb

# Some points regarding PCA:

 It is not necessary to have a target variable for applying dimensionality reduction algorithms.
 
Removing columns which have too many missing values would perform better for reducing dimensions of a data set.

Dimensionality reduction algorithms are one of the possible ways to reduce the computation time required to build a model.

t-SNE, PCA, LDA can be used to reduce dimensionality of data.

 PCA can be used for projecting and visualizing data in lower dimensions.
 
PCA is an unsupervised method

PCA searches for the directions that data have the largest variance

Maximum number of principal components <= number of features

All principal components are orthogonal to each other

t-SNE is nonlinear whereas PCA is linear

When the data is huge (in size), t-SNE may fail to produce better results.

PCA maximize the variance of the data

When all eigenvectors are the same, in such a case you won’t be able to select the principal components because in that case all principal components are equal and PCA would perform badly.

# PCA works better if there is:

A linear structure in the data

If the data lies on a curved surface and not on a flat surface

If variables are scaled in the same unit

# When you get features in lower dimensions using PCA:

The features will lose interpretability

The features may not carry all information present in data

You don’t need to initialize parameters in PCA

PCA can’t be trapped into local minima problem

# Limitations:
- PCA is not scale invariant

- The directions with largest variance are assumed to be of most interest

- Only considers orthogonal transformations (rotations) of the original variables

- PCA is only based on the mean vector and covariance matrix. Some distributions (multivariate normal) are characterized by this but some are not

- If the variables are correlated, PCA can achieve dimension reduction. If not, PCA just orders them according to their variances


