# Unsupervised Learning
* Unsupervised learning is the training of a machine using information that is neither classified nor labeled and allowing the algorithm to act on that information without guidance.
* The idea behind this type of learning is to group information based on similarities, patterns, and differences. 
* Unlike in supervised learning problems, unsupervised learning algorithms do not require input-to-output mappings to learn a mapping function

the goal of the model is to work on its own to discover patterns and information that was previously undetected. It mainly deals with unlabelled data.

## Clustering
* Clustering is the task of identifying similar instances with shared attributes in a dataset and group them together into cluster.
* Clustering is a popular type of unsupervised learning approach. You can even break it down further into different types of clustering
    * Exlcusive clustering
    * Overlapping clustering
    * Hierarchical clustering
    * Probalistic clustering

## Dimensionality reduction
* In supervised learning, one big challenge to handle is the number of input features that the algorithm needs to analyze.
* Dimensionality reduction is a technique used when the number of features, or dimensions, in a given dataset is too high. 
* It reduces the number of data inputs to a manageable size while also preserving the integrity of the dataset as much as possible. It is commonly used in the preprocessing data stage.

**Principal component analysis** -
* Principal component analysis (PCA) is a type of dimensionality reduction algorithm which is used to reduce redundancies and to compress datasets through feature extraction. 
* This method uses a linear transformation to create a new data representation, yielding a set of "principal components." 

**Singular value decomposition** -
* Singular value decomposition (SVD) is another dimensionality reduction approach which factorizes a matrix, A, into three, low-rank matrices. 
* SVD is denoted by the formula, 

    $A = USVT$

    where U and V are orthogonal matrices. S is a diagonal matrix, and S values are considered singular values of matrix A


**Autoencoders** - 
Autoencoders leverage neural networks to compress data and then recreate a new representation of the original data’s input.