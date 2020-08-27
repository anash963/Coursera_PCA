# PCA references and links:

https://github.com/soroosh-rz/Mathematics-for-Machine-Learning/tree/master/PCA 

https://github.com/launchcode01dl/mathematics-for-machine-learning-cousera/tree/master/course3%20-%20principle%20component%20analysis

https://www.youtube.com/watch?v=GyyrnOHwe2E

https://www.youtube.com/watch?v=4KuF5HRAQn8&t=983s

https://medium.com/analytics-vidhya/a-beginners-guide-for-dimensionality-reduction-using-principle-component-analysis-pca-c4c515ae49c1

https://wiki.pathmind.com/eigenvector

http://colah.github.io/posts/2014-10-Visualizing-MNIST/

https://www.appliedaicourse.com/lecture/11/applied-machine-learning-online-course/2906/questions-answers/2/module-2-data-science-exploratory-data-analysis-and-data-visualization

https://github.com/ranasingh-gkp/PCA-TSNE-on-MNIST-dataset/blob/master/14_15_16(PCA%2CT_SNE).ipynb

https://sebastianraschka.com/Articles/2014_pca_step_by_step.html

https://www.analyticsvidhya.com/blog/2017/03/questions-dimensionality-reduction-data-scientist/

https://mathworld.wolfram.com/OrthogonalTransformation.html

https://colah.github.io/posts/2014-10-Visualizing-MNIST/#:~:text=MNIST%20is%20a%20simple%20computer%20vision%20dataset.%20It,example%2C%20we%20might%20think%20of%20as%20something%20like%3A

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

## Matrices

https://www.randomservices.org/random/expect/Matrices.html

https://medium.com/data-science-365/statistical-and-mathematical-concepts-behind-pca-a2cb25940cd4

https://byjus.com/jee/types-of-matrices/

https://ncert.nic.in/ncerts/l/leep203.pdf

http://emathlab.com/Algebra/Matrices/Matrix2Help.php#:~:text=The%20determinant%20is%20equal%20to%20the%20sum%20of,-1%20%3D%20%5B1%2F5%5D%20and%20%5B5%5D%E2%80%A2%20%5B1%2F5%5D%20%3D%20%5B1%5D.

https://web.stanford.edu/~mrosenfe/soc_meth_proj3/matrix_OLS_NYU_notes.pdf

http://www.stat.columbia.edu/~fwood/Teaching/w4315/Fall2009/lecture_11

https://www.easycalculation.com/statistics/learn-correlation-matrix.php

http://users.stat.umn.edu/~helwig/notes/datamat-Notes.pdf

https://stattrek.com/matrix-algebra/covariance-matrix.aspx#:~:text=Variance-Covariance%20Matrix%201%20Variance.%20Variance%20is%20a%20measure,Suppose%20X%20is%20an%20n%20x%20k%20

https://en.wikipedia.org/wiki/Variance

http://statpower.net/Content/312/Lecture%20Slides/MatrixStat.pdf

https://www.youtube.com/watch?v=jQy5ovIG5Wk

https://en.wikipedia.org/wiki/Estimation_of_covariance_matrices

https://datascienceplus.com/understanding-the-covariance-matrix/

https://www.surveygizmo.com/resources/blog/variance-covariance-correlation/

https://towardsdatascience.com/let-us-understand-the-correlation-matrix-and-covariance-matrix-d42e6b643c22

https://en.wikipedia.org/wiki/Covariance_matrix

https://www.sharetechnote.com/html/Handbook_EngMath_Matrix_InnerProduct.html


